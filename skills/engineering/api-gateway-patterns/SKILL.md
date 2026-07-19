---
name: api-gateway-patterns
description: >
  Design and use API gateways effectively for routing, cross-cutting concerns, and backend aggregation.
  Use when introducing or evolving an API gateway, BFF, or edge layer.
---

# API Gateway Patterns

## Overview

An API gateway can centralize cross-cutting concerns (auth, rate limiting, routing, observability) but can also become a bottleneck or single point of failure if misused.

## When to Use

- Multiple backend services need a unified external API
- You want to apply consistent policies at the edge
- Implementing Backend-for-Frontend (BFF) patterns

## Common Responsibilities

- Routing and path rewriting
- Authentication / token validation
- Rate limiting and quotas
- Request/response transformation
- Aggregation of multiple backend calls
- TLS termination and basic security headers

## Principles

- Keep business logic out of the gateway when possible
- Make the gateway highly available and observable
- Avoid turning the gateway into a distributed monolith
- Prefer standard protocols and well-supported gateway products

## Verification

- Cross-cutting policies are consistently applied
- Gateway is not a development bottleneck
- Failure modes of the gateway are understood and mitigated
