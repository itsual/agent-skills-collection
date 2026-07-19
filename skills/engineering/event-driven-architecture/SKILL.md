---
name: event-driven-architecture
description: >
  Design event-driven systems with clear event contracts, delivery guarantees, and consumer patterns.
  Use when introducing async workflows, event buses, message queues, or reacting to domain events.
---

# Event-Driven Architecture

## Overview

Events enable loose coupling and scalability, but they also introduce complexity around ordering, delivery, and observability.

## When to Use

- Decoupling producers and consumers
- Async workflows and background processing
- Integrating multiple services via events
- Implementing domain events in DDD-style designs

## Key Design Decisions

- Event naming and schema (versioning strategy)
- Delivery guarantees (at-most-once, at-least-once, exactly-once semantics)
- Ordering requirements
- Idempotency of consumers
- Poison message handling
- Observability of event flows

## Principles

- Make events explicit and well-documented
- Prefer backward-compatible event evolution
- Design consumers to be idempotent when using at-least-once delivery
- Include correlation / causation IDs for tracing

## Verification

- Event contracts are clear and versioned
- Consumer failure modes are handled
- End-to-end flows can be traced
