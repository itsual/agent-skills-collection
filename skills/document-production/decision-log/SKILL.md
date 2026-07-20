---
name: decision-log
description: >
  Capture important decisions with context, options considered, rationale, and consequences so future readers understand why choices were made.
  Use for architecture decisions, product decisions, project trade-offs, or any significant choice that should not be lost to time.
---

# Decision Log

## Overview

Decision logs prevent organizations from re-litigating the same debates and help new people understand the “why” behind the current state.

## When to Use

- Architecture and design decisions
- Significant product or scope choices
- Process or policy decisions with lasting impact
- Any decision likely to be questioned later

## Lightweight Template

- **Title** – Short name of the decision
- **Status** – Proposed / Accepted / Superseded / Deprecated
- **Date** and **deciders**
- **Context** – What forces or problem led to this decision
- **Options considered**
- **Decision**
- **Rationale** – Why this option over the others
- **Consequences** – What becomes easier or harder
- **Follow-up actions** (if any)

## Principles

- Record decisions while the context is fresh
- Be honest about trade-offs
- Link to related ADRs, tickets, or docs
- Update status when a decision is reversed or replaced
- Keep entries short enough that people will write them

## Verification

- [ ] A future reader can understand why the decision was made
- [ ] Alternatives and trade-offs are visible
- [ ] Ownership and date are clear
