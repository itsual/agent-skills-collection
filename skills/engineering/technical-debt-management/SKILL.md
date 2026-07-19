---
name: technical-debt-management
description: >
  Identify, track, prioritize, and systematically reduce technical debt without derailing feature delivery.
  Use when debt is slowing the team, during planning, or when deciding whether to refactor now or later.
---

# Technical Debt Management

## Overview

Technical debt is a tool, not just a problem. The key is making it visible, intentional, and manageable.

## When to Use

- Planning sprints or roadmaps
- When delivery speed is noticeably impacted by past decisions
- During retrospectives or architecture reviews
- Deciding whether to pay down debt vs. ship features

## Practices

- Make debt visible (tickets, ADRs, code comments with context, dashboards)
- Distinguish deliberate debt from accidental debt
- Estimate the interest (ongoing cost) of living with the debt
- Allocate a consistent capacity for debt reduction (e.g., percentage of each cycle)
- Prefer high-interest, high-traffic areas first
- Pair debt reduction with feature work when it naturally touches the area (“boy scout rule” + targeted campaigns)

## Anti-Patterns

- Ignoring debt until it becomes a crisis
- Endless pure-refactoring initiatives with no clear outcome
- Treating all debt as equally urgent

## Verification

- Debt items are tracked and prioritized
- There is a realistic plan for reducing the highest-interest debt
- Feature work is not permanently blocked by unmanaged debt
