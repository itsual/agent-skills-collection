---
name: application-security
description: >
  Integrate application security across the SDLC — design reviews, testing, dependency risk, and secure release criteria.
  Use when hardening products, building AppSec programs, or preparing applications for hostile input environments.
---

# Application Security

## Overview

Application security protects software from abuse through design, implementation, testing, and operation. It is a lifecycle practice, not a pre-release scan only.

## When to Use

- Building or maturing AppSec programs
- High-risk application launches
- Remediation of recurring vuln classes
- Defining secure release gates

## Core Practices

- Threat model high-risk features early
- Train builders on common weakness classes (OWASP-style)
- Use SAST, DAST, and dependency scanning appropriately
- Fix root causes; track recurring patterns
- Require security review for sensitive changes
- Include security acceptance criteria in definitions of done

## Principles

- Finding vulns without fixing capacity creates backlog theater
- Frameworks and libraries shift but don’t eliminate AppSec duty
- AuthN/AuthZ and injection remain perennial high-impact areas
- Production config is part of application security

## Verification

- [ ] High-risk apps have threat models and testing coverage
- [ ] Critical findings have remediation SLAs
- [ ] Release gates include security criteria
