---
name: distributed-locking
description: >
  Implement safe distributed locks and coordination primitives when mutual exclusion is required across processes or services.
  Use when preventing double-processing, leader election, or coordinating work in a distributed system.
---

# Distributed Locking

## Overview

Distributed locks are easy to get subtly wrong. Prefer designs that minimize the need for them, and when required, use well-understood patterns and libraries.

## When to Use

- Ensuring only one worker processes a critical section
- Leader election or singleton tasks
- Preventing duplicate side effects under concurrency

## Key Considerations

- Lock correctness under process pauses, network partitions, and clock issues
- Lock timeout / fencing token needs
- Deadlock and lock-ordering risks
- Performance and availability impact of the lock service

## Principles

- Prefer idempotent designs that reduce the need for strict locking
- Use battle-tested implementations (Redis, etcd, ZooKeeper, database advisory locks, etc.) carefully
- Always consider what happens if the lock holder dies
- Prefer fencing tokens when the lock protects external side effects

## Verification

- Concurrent execution cannot produce incorrect duplicate effects
- Lock failure modes are understood and tested
- No single point of failure is introduced without justification
