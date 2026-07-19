---
name: documentation-and-adrs
description: >
  Write useful documentation and Architecture Decision Records (ADRs) that capture context and the *why*, not just the what.
  Use when making significant design decisions, onboarding new people, or when existing docs are missing or outdated.
---

# Documentation and ADRs

## Overview

Good documentation reduces bus factor and future rework. ADRs are especially valuable for recording the reasons behind decisions that are not obvious from the code.

## When to Use

- Significant architectural or design decisions
- Onboarding documentation
- Public or internal API docs
- When a decision is likely to be questioned later

## ADR Lightweight Template

```markdown
# ADR-NNN: Title

## Status
Proposed | Accepted | Deprecated | Superseded

## Context
What is the issue or force driving this decision?

## Decision
What is the change we are making?

## Consequences
What becomes easier or harder? What are the trade-offs?
```

## Principles

- Document the *why* and the alternatives considered
- Keep docs close to the code when possible
- Prefer short, living documents over large outdated ones
- Update or supersede ADRs instead of leaving contradictions

## Verification

- A new reader can understand the key decisions without talking to the original authors
- ADRs are linked from relevant code or architecture docs
