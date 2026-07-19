---
name: outbox-and-inbox-patterns
description: >
  Reliably publish and consume events/messages using the transactional outbox and inbox patterns.
  Use when you need consistent state changes + message publishing without distributed transactions.
---

# Outbox and Inbox Patterns

## Overview

The outbox pattern ensures that a database change and the corresponding message publication happen atomically. The inbox pattern helps consumers process messages exactly-once (or idempotently).

## When to Use

- Publishing domain events after a state change
- Avoiding dual-write problems between DB and message broker
- Building reliable event-driven flows

## Core Ideas

- **Outbox**: Write the business data and an “outbox” record in the same transaction; a relay publishes from the outbox
- **Inbox**: Record processed message IDs so duplicates can be ignored
- Combined with idempotent handlers for strong reliability

## Principles

- Dual writes without a transaction are a common source of bugs
- Make the relay process observable and restartable
- Clean up old outbox/inbox records with a retention policy

## Verification

- A state change is never committed without the corresponding outbox entry (and vice versa)
- Consumers can survive duplicate deliveries
