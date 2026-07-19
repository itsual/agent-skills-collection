---
name: microservices-patterns
description: >
  Design, decompose, and operate microservices with appropriate patterns for communication, data, and resilience.
  Use when splitting monoliths, designing new service boundaries, or reviewing distributed system design.
---

# Microservices Patterns

## Overview

Microservices trade deployment independence and team autonomy for operational and distributed-systems complexity. Use them deliberately.

## When to Use

- Clear bounded contexts and team ownership exist
- Independent scaling or deployment is a real requirement
- Reviewing service boundaries or inter-service communication

## Key Concerns

- Service boundaries aligned with business capabilities
- Communication style (sync vs async)
- Data ownership (database-per-service)
- Distributed transactions and sagas
- Service discovery, resilience, and observability
- Testing strategies across services

## Principles

- Prefer loose coupling and high cohesion
- Design for failure
- Make service contracts explicit and versioned
- Avoid distributed monoliths (tight coupling + independent deployability theater)

## Verification

- Boundaries have clear ownership and reasons
- Cross-service flows are observable and resilient
- Operational complexity is justified by the benefits
