---
name: data-modeling-and-persistence
description: >
  Design clear data models, schemas, and persistence strategies that balance integrity, performance, and evolvability.
  Use when defining database schemas, choosing storage, or modeling domain data.
---

# Data Modeling and Persistence

## Overview

Data usually outlives code. Invest in clear models, constraints, and migration strategies.

## When to Use

- Designing new tables/collections or domain models
- Choosing between relational, document, key-value, etc.
- Planning schema migrations
- Addressing data integrity or query performance issues

## Core Practices

- Model the domain first; let storage concerns inform but not fully dictate the model
- Use constraints (not just application code) to protect integrity where appropriate
- Plan for schema evolution from the start
- Index deliberately based on actual access patterns
- Consider consistency, availability, and partition tolerance trade-offs explicitly
- Separate read and write models when the complexity is justified (CQRS-style)

## Migration Discipline

- Prefer expandable, backward-compatible changes when possible
- Test migrations against realistic data volumes
- Have a rollback or forward-fix strategy

## Verification

- Critical invariants are enforced
- Common queries are efficiently supported
- Schema changes are safe and reversible or clearly one-way
