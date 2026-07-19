---
name: rate-limiting-and-throttling
description: >
  Protect systems and fair usage with appropriate rate limiting, throttling, and quota strategies.
  Use when designing public APIs, protecting backends, or controlling resource consumption.
---

# Rate Limiting and Throttling

## Overview

Rate limiting protects system stability and enforces fair usage. Poorly designed limits frustrate users or fail to protect the system.

## When to Use

- Public or multi-tenant APIs
- Expensive operations
- Protecting downstream dependencies
- Defending against abuse or accidental overload

## Design Considerations

- What is being limited (IP, user, API key, tenant, endpoint)?
- Algorithm (token bucket, sliding window, fixed window, etc.)
- Response behavior (429 + Retry-After headers)
- Visibility and override mechanisms for legitimate high-volume consumers
- Distributed vs local limiting

## Principles

- Fail closed under extreme load when necessary
- Provide clear feedback to clients
- Make limits configurable and observable

## Verification

- Limits behave as documented
- Legitimate traffic is not unduly impacted
- System remains stable under bursty or abusive load
