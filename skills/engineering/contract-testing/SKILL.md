---
name: contract-testing
description: >
  Use consumer-driven or bidirectional contract tests to keep service interfaces compatible across independent deployability.
  Use when multiple services or teams share APIs and need confidence that changes won’t break consumers.
---

# Contract Testing

## Overview

Contract tests verify that a provider still satisfies the expectations of its consumers without requiring full end-to-end deployments for every change.

## When to Use

- Microservices or multi-team environments with shared APIs
- Independent deployment of producers and consumers
- Reducing reliance on slow, brittle E2E tests for interface compatibility

## Approaches

- Consumer-driven contracts (e.g. Pact-style)
- Provider-driven / schema-based verification
- Bidirectional contracts

## Principles

- Contracts should reflect real consumer expectations
- Keep contracts focused and maintainable
- Integrate verification into CI for both consumer and provider
- Version and evolve contracts deliberately

## Verification

- Provider CI verifies it still meets published contracts
- Consumer CI verifies it works against the contract (or a stub derived from it)
- Breaking changes are detected before production
