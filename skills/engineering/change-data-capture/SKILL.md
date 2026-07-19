---
name: change-data-capture
description: >
  Capture and propagate database changes reliably using Change Data Capture (CDC) patterns.
  Use when synchronizing data between systems, building event streams from databases, or implementing cache invalidation based on DB changes.
---

# Change Data Capture

## Overview

CDC turns database changes into a stream of events, enabling downstream systems to react without dual writes or heavy polling.

## When to Use

- Feeding search indexes, caches, or analytics from a source of truth database
- Building event streams from existing applications with minimal application changes
- Integrating multiple systems around shared data

## Key Considerations

- Source database support and impact (triggers, transaction logs, etc.)
- Ordering and consistency guarantees
- Schema change handling
- Exactly-once vs at-least-once delivery to downstream consumers
- Initial snapshot + ongoing changes
- Monitoring lag and failures

## Principles

- Prefer log-based CDC over trigger-based when available and appropriate
- Design consumers to be idempotent
- Make lag and error states highly visible

## Verification

- Changes are captured completely and in order (within documented guarantees)
- Downstream systems can catch up after failures
- Schema evolution does not silently break the pipeline
