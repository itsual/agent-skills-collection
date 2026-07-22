---
name: data-contracts
description: >
  Define and enforce data contracts between producers and consumers — schema, semantics, SLAs, and compatibility rules — to prevent breaking changes.
  Use when scaling data products, reducing pipeline breakages, or formalizing producer accountability.
---

# Data Contracts

## Overview

Data contracts are explicit agreements about what a data product provides: structure, meaning, freshness, and change policy. They shift quality left to producers.

## When to Use

- Producer/consumer friction on schema changes
- Publishing analytical or operational data products
- Microservices or event streams consumed by many teams
- Reducing emergency fire drills from unexpected upstream changes

## Core Practices

- Specify schema, types, keys, and allowed nullability
- Document semantics and grain in human language
- Define SLAs (freshness, completeness) and support channels
- Set compatibility rules (backward/forward) and versioning
- Validate contracts in CI before producers deploy changes
- Version and communicate breaking changes with migration windows

## Principles

- Implicit contracts are where outages hide
- Consumers should not reverse-engineer semantics from samples alone
- Enforcement in pipelines beats documentation-only agreements
- Start contracts on the highest-churn, highest-impact interfaces

## Verification

- [ ] Critical interfaces have written contracts
- [ ] Validation runs before breaking changes ship
- [ ] Consumers know how to get support and change notices
