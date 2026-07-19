---
name: api-and-interface-design
description: >
  Design stable, well-documented, and evolvable APIs and interfaces (REST, GraphQL, internal modules, libraries).
  Use when creating or significantly changing public or internal APIs, contracts, or module boundaries.
---

# API and Interface Design

## Overview

Good interfaces are hard to change later. Invest in clarity, consistency, and evolvability up front.

## When to Use

- Designing new endpoints or services
- Changing existing public contracts
- Defining module or library boundaries
- Reviewing API proposals

## Core Principles

- **Clarity over cleverness**
- Consistent naming and structure
- Explicit error models
- Backward compatibility as the default
- Documentation lives with the contract

## Process

1. Identify consumers and their needs
2. Define resources/operations and their semantics
3. Design request/response shapes and error cases
4. Consider versioning and evolution strategy
5. Document with examples
6. Review for consistency with existing APIs

## Checklist

- [ ] Resource naming is consistent and intuitive
- [ ] HTTP methods (or equivalent) used correctly
- [ ] Pagination, filtering, sorting considered where relevant
- [ ] Error responses are structured and actionable
- [ ] Authentication/authorization model is clear
- [ ] Breaking changes are avoided or explicitly versioned
- [ ] Examples are provided

## Verification

- Contract is reviewable without reading implementation
- Common consumer scenarios are expressible cleanly
- Evolution path exists for likely future needs
