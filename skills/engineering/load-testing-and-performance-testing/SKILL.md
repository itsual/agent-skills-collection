---
name: load-testing-and-performance-testing
description: >
  Design and run load, stress, and performance tests that produce actionable results about system behavior under expected and peak load.
  Use when validating scalability, setting performance budgets, or investigating performance issues.
---

# Load Testing and Performance Testing

## Overview

Performance tests answer questions about capacity, latency, and stability under load. They are most valuable when tied to realistic scenarios and clear success criteria.

## When to Use

- Before major launches or traffic events
- Validating scalability claims or capacity plans
- Regression testing performance-sensitive paths
- Investigating production performance issues

## Core Practices

- Define clear goals (latency percentiles, error rates, throughput)
- Model realistic user behavior and data volumes
- Include think time and ramp-up patterns
- Monitor the system under test (not just the load generator)
- Distinguish load, stress, soak, and spike tests
- Automate where it provides ongoing regression value

## Principles

- Test the system the way it will actually be used
- Measure from the outside (user-visible) and the inside (resource utilization)
- Treat performance regressions as bugs when budgets exist

## Verification

- Results are reproducible enough to be useful
- Bottlenecks identified are real and actionable
- Performance budgets or SLOs have been checked against the results
