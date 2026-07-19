---
name: backpressure-and-flow-control
description: >
  Design systems that apply backpressure and flow control so producers do not overwhelm consumers.
  Use when building streaming, messaging, or pipelined systems that must remain stable under load.
---

# Backpressure and Flow Control

## Overview

Without backpressure, fast producers can overwhelm slow consumers, leading to unbounded queues, memory exhaustion, and cascading failures.

## When to Use

- Streaming data pipelines
- Message consumers and event processors
- Any system with producers and consumers operating at different speeds

## Techniques

- Bounded queues with clear overflow behavior
- Reactive streams / async pull-based models
- Rate limiting and load shedding
- Credit-based or window-based flow control
- Circuit breaking when downstream is unhealthy

## Principles

- Prefer signaling upstream to slow down over unbounded buffering
- Make overload behavior explicit and observable
- Drop, sample, or reject work according to clear policy when necessary

## Verification

- System remains stable when consumers slow down or stop
- Overload behavior is tested and documented
- Key metrics (queue depth, drop rate, latency) are visible
