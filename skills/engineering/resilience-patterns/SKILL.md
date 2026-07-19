---
name: resilience-patterns
description: >
  Apply proven resilience patterns (retries, circuit breakers, timeouts, bulkheads, fallbacks) so systems degrade gracefully under failure.
  Use when designing distributed systems, integrating external services, or improving production robustness.
---

# Resilience Patterns

## Overview

Failure is normal in distributed systems. Design for it deliberately.

## When to Use

- Calling external services or dependencies
- Designing microservices or multi-component systems
- Improving behavior under load or partial outages

## Core Patterns

- **Timeouts** – Always set them; never wait forever
- **Retries** – With backoff and jitter; only for transient errors
- **Circuit breakers** – Prevent cascading failures
- **Bulkheads** – Isolate resources so one failure doesn’t take everything down
- **Fallbacks** – Provide degraded but useful behavior when possible
- **Rate limiting / load shedding** – Protect the system from overload

## Principles

- Make failure modes explicit
- Prefer fast failure over prolonged degradation when appropriate
- Observe and alert on resilience mechanisms (open circuits, retry rates, etc.)
- Test failure scenarios (chaos or fault injection where justified)

## Verification

- Critical external calls have timeouts and sensible retry policies
- Cascading failure risks are identified and mitigated
- Behavior under dependency failure is understood
