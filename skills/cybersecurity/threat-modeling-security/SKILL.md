---
name: threat-modeling-security
description: >
  Threat model systems to identify attackers, entry points, assets, and mitigations before build or major change.
  Use when designing features, reviewing architecture, or prioritizing security work against realistic threats.
---

# Threat Modeling

## Overview

Threat modeling asks what can go wrong, who might cause it, and what we will do about it — early enough to change design cheaply.

## When to Use

- New products, features, or major architecture changes
- High-risk data flows (auth, payments, PII, admin)
- Third-party integration reviews
- Prioritizing backlog security items

## Core Practices

- Diagram the system: actors, trust boundaries, data flows
- Identify assets and what “bad” looks like for each
- Enumerate threats (STRIDE or equivalent structured method)
- Rate risk and choose mitigations or acceptances
- Track findings to closure in the backlog
- Revisit when the design or threat landscape changes

## Principles

- A threat model that never changes a design was theater
- Focus on realistic adversaries for your context
- Trust boundaries are where many controls belong
- Document accepted risks explicitly

## Verification

- [ ] Data flow and trust boundaries are explicit
- [ ] Material threats have mitigations or acceptance
- [ ] Findings are tracked to resolution
