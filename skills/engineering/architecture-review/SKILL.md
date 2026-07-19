---
name: architecture-review
description: >
  Evaluate system or component design for scalability, maintainability, security, and alignment with goals.
  Use when proposing or reviewing significant architectural changes, new services, or major refactors.
---

# Architecture Review

## Overview

Architecture decisions have long-lived consequences. Review them explicitly against quality attributes and constraints.

## When to Use

- New services or major components
- Significant refactors or re-architecture proposals
- When quality attributes (scale, latency, consistency, etc.) are critical

## Review Dimensions

- Fitness for purpose and goals
- Scalability and performance characteristics
- Maintainability and team cognitive load
- Security and data integrity
- Operability (deploy, monitor, debug)
- Cost and complexity
- Alignment with existing architecture and standards

## Process

1. Restate goals and constraints
2. Examine the proposed design and key alternatives
3. Evaluate against the dimensions above
4. Call out risks, unknowns, and recommended mitigations
5. Record major decisions (ideally as ADRs)

## Verification

- Key quality attributes have been explicitly considered
- Major risks are documented with mitigation or acceptance
- Decision rationale is captured for future readers
