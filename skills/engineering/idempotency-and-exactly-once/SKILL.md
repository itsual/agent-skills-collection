---
name: idempotency-and-exactly-once
description: >
  Design operations to be safely retryable and handle duplicate execution correctly.
  Use when building APIs, message consumers, or any operation that may be retried or delivered more than once.
---

# Idempotency and Exactly-Once Semantics

## Overview

In distributed systems, “exactly-once” is hard. Most practical systems aim for at-least-once delivery + idempotent handlers.

## When to Use

- Payment or state-changing APIs
- Message / event consumers
- Any operation that clients or infrastructure may retry

## Techniques

- Idempotency keys
- Natural idempotency (set-based operations, upserts)
- Deduplication stores with appropriate TTLs
- Outbox pattern for reliable publishing
- Transactional messaging where supported

## Principles

- Assume duplicates will happen
- Make the side effects of duplicate execution safe or detectable
- Document the idempotency guarantees of your APIs

## Verification

- Retrying the same request/message does not produce incorrect duplicate effects
- Idempotency behavior is tested
