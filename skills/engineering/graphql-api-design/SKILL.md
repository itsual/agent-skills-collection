---
name: graphql-api-design
description: >
  Design well-structured, evolvable, and performant GraphQL APIs with clear schemas, pagination, and error handling.
  Use when building or reviewing GraphQL endpoints, schemas, or resolvers.
---

# GraphQL API Design

## Overview

GraphQL gives clients flexibility but shifts complexity to the server. Good schema design, authorization, and performance controls are essential.

## When to Use

- Designing new GraphQL APIs or schemas
- Reviewing resolver structure, N+1 risks, or authorization
- Evolving existing GraphQL contracts

## Key Practices

- Design the schema around client use cases and domain concepts
- Use clear naming and consistent patterns for connections/pagination
- Protect against expensive queries (depth limiting, complexity analysis, timeouts)
- Handle errors with a consistent structure
- Apply authorization at the field/resolver level where needed
- Prefer explicit input types and avoid overly generic mutations
- Versioning is usually evolutionary — deprecate fields carefully

## Common Pitfalls

- N+1 query problems in resolvers
- Over-fetching allowed by unbounded queries
- Weak authorization (assuming the client will only ask for allowed data)
- Giant “god” types or mutations

## Verification

- Critical queries and mutations are efficient and authorized
- Schema changes follow a deprecation strategy
- Expensive query protection is in place
