---
name: threat-modeling
description: >
  Systematically identify and prioritize security threats to a system and decide on mitigations.
  Use when designing new systems, reviewing architecture, or improving security posture of existing systems.
---

# Threat Modeling

## Overview

Threat modeling is a structured way to think about what can go wrong and what you are going to do about it.

## When to Use

- Designing new features or systems with security implications
- Reviewing architecture for security weaknesses
- Prioritizing security work

## Lightweight Process

1. **What are we building?** (diagrams, data flows, trust boundaries)
2. **What can go wrong?** (STRIDE or similar: Spoofing, Tampering, Repudiation, Information Disclosure, Denial of Service, Elevation of Privilege)
3. **What are we going to do about it?** (mitigate, accept, transfer, avoid)
4. **Did we do a good job?** (review and iterate)

## Principles

- Focus on the highest-impact, most likely threats first
- Involve people who know the system and the domain
- Keep models living — update when the system changes significantly
- Prefer concrete mitigations over generic advice

## Verification

- Key assets and trust boundaries are identified
- Important threats have explicit decisions (mitigate / accept)
- Mitigations are tracked and implemented
