---
name: background-jobs-and-async-processing
description: >
  Design reliable background jobs, queues, and asynchronous processing with proper retries, visibility, and failure handling.
  Use when offloading work from request/response paths or building async workflows.
---

# Background Jobs and Async Processing

## Overview

Moving work out of the critical request path improves responsiveness and scalability, but introduces new failure modes that must be handled deliberately.

## When to Use

- Long-running or resource-intensive tasks
- Work that can be eventually consistent
- Decoupling producers from consumers
- Scheduled or recurring work

## Key Design Points

- Idempotency of job handlers
- Retry strategy with backoff
- Dead-letter / failed job handling
- Visibility timeouts and at-least-once delivery realities
- Observability (queue depth, processing latency, failure rates)
- Ordering requirements (if any)

## Principles

- Prefer simple, well-understood queue systems unless complexity is justified
- Make jobs restartable and side-effect safe
- Surface failures clearly

## Verification

- Failed jobs are visible and recoverable
- Duplicate execution does not cause incorrect results
- Key metrics are monitored
