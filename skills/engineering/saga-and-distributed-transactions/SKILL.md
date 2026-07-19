---
name: saga-and-distributed-transactions
description: >
  Coordinate multi-step business processes across services using sagas or other distributed transaction patterns.
  Use when a single business action requires consistent updates in multiple systems or services.
---

# Saga and Distributed Transactions

## Overview

Classic ACID transactions do not scale across services. Sagas and related patterns provide a practical way to manage long-running, multi-step processes with eventual consistency.

## When to Use

- Business processes that span multiple services or data stores
- Need for compensation logic when a later step fails
- Replacing distributed 2PC with more resilient approaches

## Core Ideas

- Break the process into local transactions + compensating actions
- Choreography (events) vs Orchestration (central coordinator)
- Idempotency and timeout handling are essential
- Make the current state of the saga visible and recoverable

## Principles

- Prefer orchestration when the process is complex or needs clear visibility
- Design compensating actions carefully — they are also business logic
- Surface failures and allow manual intervention when automatic compensation is insufficient

## Verification

- Failure at each step has a defined recovery or compensation path
- Saga state can be inspected and recovered
- Duplicate messages do not corrupt the process
