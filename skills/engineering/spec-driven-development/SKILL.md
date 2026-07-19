---
name: spec-driven-development
description: >
  Create clear specifications and acceptance criteria before writing code.
  Use for any new feature, significant change, or when requirements are ambiguous.
  Trigger when the user says "spec", "requirements", "what should we build", or before starting non-trivial implementation.
---

# Spec-Driven Development

## Overview

Write a lightweight but precise specification before implementation. This prevents the most common agent failure mode: building the wrong thing confidently.

## When to Use

- New features or user stories
- Significant refactors or architectural changes
- Ambiguous requests
- Before any non-trivial coding work

## Core Process

### 1. Capture Intent
What problem are we solving? For whom? Why now?

### 2. Define Success
What does "done" look like from the user’s perspective?

### 3. Write the Spec
Keep it short. Focus on:

- **Problem statement**
- **Goals** (and non-goals)
- **User-facing behavior**
- **Acceptance criteria** (testable)
- **Edge cases & error handling**
- **Constraints** (performance, compatibility, security, etc.)
- **Open questions**

### 4. Review & Agree
Surface the spec to the user for confirmation before coding.

## Recommended Spec Template

```markdown
# Spec: [Feature Name]

## Problem
...

## Goals
- ...

## Non-Goals
- ...

## User Stories / Behavior
- As a ... I want ... so that ...

## Acceptance Criteria
- [ ] ...
- [ ] ...

## Edge Cases
- ...

## Technical Notes / Constraints
- ...

## Open Questions
- ...
```

## Principles

- Prefer concrete, testable statements over vague ones
- Explicitly call out non-goals to prevent scope creep
- Keep the spec living — update it if requirements change
- A good spec makes implementation and review much easier

## Verification

Before writing code, confirm:
- The user has seen and agreed with the spec (or key parts)
- Acceptance criteria are specific enough to test against
- Major assumptions are documented
