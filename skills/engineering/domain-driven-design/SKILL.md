---
name: domain-driven-design
description: >
  Apply Domain-Driven Design tactical and strategic patterns to model complex business domains clearly.
  Use when building complex business logic, defining bounded contexts, aggregates, or ubiquitous language.
---

# Domain-Driven Design

## Overview

DDD helps manage complexity by aligning the code model with the business domain and explicitly defining boundaries.

## When to Use

- Complex business domains with rich rules
- Multiple teams working on related but distinct areas
- When the existing model is becoming a “big ball of mud”

## Key Concepts

- **Ubiquitous Language** – Shared language between domain experts and developers
- **Bounded Contexts** – Explicit boundaries where a model applies
- **Aggregates** – Consistency boundaries
- **Entities vs Value Objects**
- **Domain Events**
- **Anti-Corruption Layers** when integrating with other systems

## Practical Guidance

- Start with the domain, not the database or framework
- Keep aggregates small
- Prefer eventual consistency across aggregates when appropriate
- Use context maps to understand relationships between bounded contexts
- Don’t force full DDD on simple CRUD areas

## Verification

- Core domain logic is expressed in domain terms
- Boundaries between contexts are clear
- Invariants are protected inside aggregates
