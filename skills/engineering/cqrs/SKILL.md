---
name: cqrs
description: >
  Apply Command Query Responsibility Segregation to separate read and write models when their needs diverge significantly.
  Use when read and write performance, scaling, or model complexity requirements are very different.
---

# CQRS

## Overview

CQRS separates the model used for updates from the model used for reads. It is powerful but adds complexity and should be used when the benefits are clear.

## When to Use

- Read and write workloads have very different shapes or scale requirements
- Complex domains where a single model becomes awkward
- Event-sourced systems (often paired with CQRS)

## Key Points

- Commands change state; queries return data without side effects
- Different models (and sometimes different stores) for reads vs writes
- Eventual consistency between write side and read side is common
- Requires clear discipline around where validation and business rules live

## Principles

- Don’t apply CQRS by default — it increases moving parts
- Start with a single model and separate only when pain appears
- Make consistency expectations explicit to clients

## Verification

- Write-side invariants are protected
- Read models are updated reliably (or lag is acceptable and visible)
- Complexity is justified by measurable benefits
