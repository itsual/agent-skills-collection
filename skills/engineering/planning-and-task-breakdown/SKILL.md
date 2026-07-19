---
name: planning-and-task-breakdown
description: >
  Break complex work into small, verifiable tasks with clear acceptance criteria.
  Use whenever starting a non-trivial feature, refactor, or project, or when the user asks for a plan, task list, breakdown, or roadmap of implementation steps.
  Prefer this skill before writing significant code.
---

# Planning and Task Breakdown

## Overview

Turn ambiguous or large goals into a sequence of small, independently verifiable tasks. Good planning dramatically increases the success rate of agent-driven work.

## When to Use

- Starting any non-trivial feature or change
- User asks for a plan, breakdown, tasks, or implementation steps
- Before beginning coding on a new area
- When a previous attempt failed due to scope or unclear requirements

## Core Process

### 1. Clarify the Goal
Restate the objective in one or two sentences. Surface assumptions explicitly:

```
ASSUMPTIONS:
1. ...
2. ...
→ Correct me if any of these are wrong.
```

### 2. Identify Scope Boundaries
What is explicitly in scope? What is out of scope for this iteration?

### 3. Decompose into Vertical Slices
Prefer thin vertical slices (end-to-end value) over horizontal layers when possible.

Each task should be:
- Small enough to complete and verify in one focused session
- Independently testable
- Ordered by dependency

### 4. Write Clear Acceptance Criteria
For every task, define how we will know it is done (tests, behavior, observable outcome).

### 5. Sequence and Estimate Roughly
Order tasks. Note any that can be parallelized.

## Output Format

Produce a structured plan:

```markdown
## Goal
[One sentence]

## Assumptions
- ...

## Out of Scope
- ...

## Tasks

### Task 1: [Short title]
**Description**: ...
**Acceptance criteria**:
- [ ] ...
- [ ] ...
**Dependencies**: none / Task X

### Task 2: ...
```

## Quality Checks

- Are tasks small enough?
- Does each have verifiable acceptance criteria?
- Is the first task a good starting point (low risk, high learning)?
- Have major risks or unknowns been called out?

## Common Pitfalls

- Tasks that are still too large ("Implement the whole auth system")
- Missing acceptance criteria
- Hidden assumptions not surfaced
- Starting implementation before the plan is agreed

## Verification

A good plan lets another agent (or human) pick up any task and know exactly what "done" looks like without further clarification.
