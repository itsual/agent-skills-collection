---
name: api-versioning-and-compatibility
description: >
  Design APIs and contracts for safe evolution, backward compatibility, and clear versioning strategies.
  Use when releasing public or internal APIs that will have multiple consumers over time.
---

# API Versioning and Compatibility

## Overview

Changing an API after consumers depend on it is expensive. Design for evolution from the start.

## When to Use

- Designing new public or widely-used internal APIs
- Making changes to existing contracts
- Choosing between URL versioning, header versioning, or evolutionary approaches

## Strategies

- **Backward-compatible changes** whenever possible (add fields, don’t remove or redefine)
- Explicit versioning (URL path, header, or media type) when breaking changes are required
- Deprecation windows and clear communication
- Consumer-driven contract testing where justified

## Principles

- Prefer additive, non-breaking changes
- Document compatibility guarantees
- Make breaking changes rare, explicit, and well-communicated
- Version only when necessary — excessive versioning has its own costs

## Verification

- Compatibility expectations are documented
- Breaking changes follow a clear process
- Consumers have a realistic migration path
