---
name: caching-strategies
description: >
  Design appropriate caching layers and invalidation strategies to improve performance without creating consistency nightmares.
  Use when adding caches, facing performance issues related to repeated computation or data fetching, or reviewing cache usage.
---

# Caching Strategies

## Overview

Caching can dramatically improve performance and reduce load, but incorrect caching introduces subtle bugs and stale data problems.

## When to Use

- Hot read paths
- Expensive computations or external calls
- Reviewing existing cache usage for correctness or effectiveness

## Key Questions

- What is the cost of a cache miss vs. a stale read?
- What is the invalidation or expiration strategy?
- Is the cache local, distributed, or both?
- How do we observe hit rates and stampede behavior?

## Common Patterns

- Cache-aside
- Read-through / write-through
- Write-behind (use with caution)
- Time-based expiration + explicit invalidation
- Request coalescing / singleflight to prevent stampedes

## Principles

- Cache what is expensive and relatively stable
- Make consistency requirements explicit
- Prefer simple invalidation over complex speculative caching when correctness matters
- Monitor hit rate, latency, and error rates

## Verification

- Stale data behavior is understood and acceptable
- Cache failures degrade gracefully
- Hit rates and effectiveness are measurable
