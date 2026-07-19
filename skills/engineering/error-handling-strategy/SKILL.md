---
name: error-handling-strategy
description: >
  Design consistent, informative, and safe error handling across the stack.
  Use when defining how failures are detected, reported, logged, and surfaced to users or callers.
---

# Error Handling Strategy

## Overview

Good error handling improves debuggability, user experience, and system resilience. Inconsistent or leaky error handling is a common source of production pain.

## When to Use

- Designing new services or APIs
- Reviewing existing error paths
- Standardizing error codes, messages, or exception hierarchies
- Improving observability of failures

## Core Principles

- Fail fast for programmer errors; handle expected failures gracefully
- Preserve context (correlation IDs, causes) without leaking sensitive data
- Make errors actionable for both operators and (when appropriate) end users
- Prefer explicit error types/codes over generic catch-alls
- Log at the right level with enough context to diagnose

## Recommended Practices

- Distinguish between domain/business errors and technical/infrastructure errors
- Use structured error responses for APIs
- Avoid exposing internal stack traces or secrets to clients
- Ensure transient errors are retried appropriately (see resilience patterns)
- Centralize mapping of internal errors to external representations where helpful

## Verification

- Common failure modes have clear, consistent handling
- Logs and metrics make it possible to diagnose production errors
- User-facing messages are helpful without being dangerous
