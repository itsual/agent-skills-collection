---
name: api-security
description: >
  Secure APIs — authentication, authorization, input validation, rate limiting, and inventory of exposed endpoints.
  Use when designing, reviewing, or testing API-heavy applications and integrations.
---

# API Security

## Overview

APIs are application attack surface with machine-scale access. Broken auth, excessive data exposure, and lack of inventory are recurring failure modes.

## When to Use

- API design and gateway policy
- Reviewing microservices and mobile backends
- Third-party API integration security
- Testing for OWASP API Top risks

## Core Practices

- Inventory all APIs including shadow and deprecated endpoints
- Authenticate strongly; authorize at object and function level
- Validate inputs and enforce schemas
- Rate-limit and detect abuse patterns
- Minimize data returned; avoid mass assignment flaws
- Log access and anomalies for API traffic

## Principles

- Security through obscurity of endpoint URLs is not control
- “Internal only” APIs become external under misconfig or SSRF
- Broken object-level authorization is a top real-world issue
- Versioning and decommissioning reduce long-lived weak endpoints

## Verification

- [ ] API inventory is reasonably complete
- [ ] AuthZ checks are enforced server-side per object
- [ ] Rate limits and logging exist on public APIs
