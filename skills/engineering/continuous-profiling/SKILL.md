---
name: continuous-profiling
description: >
  Use continuous profiling to understand where production CPU, memory, and other resources are spent over time.
  Use when optimizing performance, investigating resource usage, or building a culture of efficiency.
---

# Continuous Profiling

## Overview

Continuous profiling collects performance data from production (or production-like) environments on an ongoing basis, making it possible to see real-world resource consumption patterns.

## When to Use

- Investigating high CPU, memory, or allocation costs
- Optimizing efficiency at scale
- Comparing performance before/after changes in real traffic

## Practices

- Prefer low-overhead continuous profilers suitable for production
- Correlate profiles with deployments, traffic patterns, and incidents
- Focus optimization effort on the hottest, most costly paths
- Combine with tracing and metrics for full context

## Principles

- Production data beats synthetic benchmarks for many optimization questions
- Profile-guided optimization should be driven by evidence, not intuition

## Verification

- Profiles are available for key services with acceptable overhead
- Teams can answer “where is the CPU/memory going?” with data
