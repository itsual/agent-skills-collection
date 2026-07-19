---
name: performance-optimization
description: >
  Measure first, then optimize the actual bottlenecks. Use when addressing slowness, high resource usage, or when performance requirements exist.
---

# Performance Optimization

## Overview

Premature optimization wastes effort. Always measure, identify the real bottleneck, then improve it with the simplest effective change.

## When to Use

- Users report slowness
- Performance budgets or SLOs exist
- Profiling shows hotspots
- Scaling concerns arise

## Core Process

1. **Define the goal** – What latency, throughput, or resource target?
2. **Measure** – Establish a reliable baseline with realistic load/data.
3. **Locate the bottleneck** – Profile; do not guess.
4. **Improve** – Make the smallest change that meaningfully moves the metric.
5. **Re-measure** – Confirm the improvement and check for regressions.
6. **Guard** – Add monitoring or tests if the area is critical.

## Common Hotspots

- N+1 queries / missing indexes
- Unbounded data fetching
- Excessive serialization or memory allocation
- Synchronous work that can be async or cached
- Frontend re-renders or large bundles
- Lock contention

## Principles

- Optimize for the common case
- Prefer algorithmic improvements over micro-optimizations
- Keep changes measurable and reversible
- Document non-obvious performance decisions

## Verification

- Before/after numbers exist
- No significant regression in correctness or other metrics
- Monitoring covers the improved path if it is critical
