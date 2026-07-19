---
name: data-contracts
description: >
  Define and enforce explicit data contracts between data producers and consumers to improve reliability and reduce breaking changes.
  Use when multiple teams share datasets, pipelines, or analytical tables.
---

# Data Contracts

## Overview

Data contracts make the expectations between data producers and consumers explicit, testable, and enforceable — similar to API contracts but for data.

## When to Use

- Multiple teams depend on shared tables, streams, or files
- Breaking changes in data are causing downstream failures
- Moving toward a more product-oriented data culture

## Key Elements of a Contract

- Schema and types
- Ownership and SLAs (freshness, quality)
- Compatibility / change policy
- Quality checks and monitoring
- Semantics and business meaning of fields

## Principles

- Treat important datasets as products with interfaces
- Prefer explicit contracts over tribal knowledge
- Enforce contracts with tests and monitoring, not just documentation

## Verification

- Consumers can rely on documented guarantees
- Breaking changes follow a defined process
- Quality and freshness are monitored against the contract
