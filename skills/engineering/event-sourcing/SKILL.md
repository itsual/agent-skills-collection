---
name: event-sourcing
description: >
  Persist state as a sequence of events rather than mutable current-state only, enabling audit, replay, and temporal queries.
  Use when auditability, time-travel, or complex domain event history is a core requirement.
---

# Event Sourcing

## Overview

Event sourcing stores every change as an immutable event. Current state is derived by replaying events. It is powerful but significantly increases complexity.

## When to Use

- Strong audit or regulatory requirements
- Need to reconstruct past states or debug by replaying history
- Complex domains where the journey matters as much as the destination

## Key Considerations

- Event schema design and evolution
- Snapshots for performance
- Rebuilding read models / projections
- Idempotency and concurrency control (optimistic locking on streams)
- Privacy and “right to be forgotten” become harder

## Principles

- Don’t choose event sourcing lightly — it is not a free upgrade
- Treat event schemas with the same care as public APIs
- Make projections rebuildable

## Verification

- Events are immutable and append-only in practice
- Projections can be rebuilt from events
- Performance of replay/snapshot strategy is acceptable
