---
name: authorization-patterns
description: >
  Design robust authorization (RBAC, ABAC, ReBAC, policy-based) and enforce it consistently on every sensitive action.
  Use when controlling access to resources, actions, or data.
---

# Authorization Patterns

## Overview

Authentication answers “who are you?”. Authorization answers “what are you allowed to do?”. Enforce it on the server for every sensitive operation.

## When to Use

- Defining roles, permissions, or policies
- Protecting APIs, UI actions, or data access
- Implementing multi-tenant isolation
- Reviewing for IDOR or privilege escalation risks

## Common Models

- **RBAC** – Role-Based Access Control (simple, widely used)
- **ABAC** – Attribute-Based (more flexible, policy-driven)
- **ReBAC** – Relationship-Based (useful for complex ownership/sharing graphs)
- Permission checks co-located with the action vs. centralized policy engines

## Principles

- Deny by default
- Check authorization on every sensitive operation (never rely only on UI hiding)
- Keep policies auditable and testable
- Prefer explicit grants over complex inheritance when possible
- Consider tenant isolation as a first-class concern in multi-tenant systems

## Verification

- Positive and negative authorization tests exist for critical paths
- IDOR-style attacks are considered and mitigated
- Policy changes are reviewable
