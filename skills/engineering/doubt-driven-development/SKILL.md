---
name: doubt-driven-development
description: >
  Perform adversarial, fresh-context review of non-trivial decisions while building.
  Use when making architectural choices, complex logic, or any decision that will be expensive to reverse. Trigger on high-stakes implementation work or when you want a "second opinion" from a clean perspective.
---

# Doubt-Driven Development

## Overview

Confidence is not the same as correctness. Periodically step back and attack your own decisions with a fresh perspective before they become expensive to change.

## When to Use

- Non-trivial architectural or design decisions
- Complex business logic or state machines
- Security-sensitive or data-integrity paths
- When the implementation has grown larger than originally expected
- Before finalizing a significant abstraction

## Core Process

1. Pause and restate the decision and its alternatives.
2. Ask: "What would a skeptical staff engineer challenge here?"
3. Explicitly list assumptions and failure modes.
4. Consider the cost of being wrong vs. the cost of more investigation.
5. Either strengthen the decision with evidence or choose a simpler/safer path.
6. Document the key trade-off if it is non-obvious.

## Useful Questions

- What is the simplest thing that could work?
- What happens under failure or partial failure?
- How hard will this be to change in 6 months?
- Are we solving a real problem or a hypothetical one?
- Is this abstraction earning its complexity?

## Verification

- Major decisions have been stress-tested with at least one adversarial pass
- Key assumptions are written down
- Simpler alternatives were considered and rejected for clear reasons
