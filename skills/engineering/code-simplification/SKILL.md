---
name: code-simplification
description: >
  Reduce unnecessary complexity while preserving behavior. Use when code is hard to understand, overly abstracted, or when a simpler design would suffice.
---

# Code Simplification

## Overview

Complexity is a cost. Remove it when it is not earning its keep.

## When to Use

- After a feature is working but the code feels heavy
- During review when complexity is flagged
- When onboarding or modifying an area that is difficult to understand

## Process

1. Ensure behavior is protected by tests (add characterization tests if needed)
2. Identify complexity that does not pull its weight (extra abstractions, deep nesting, speculative generality)
3. Simplify while keeping tests green
4. Prefer deletion and flattening over adding more structure

## Heuristics

- Can this be done in fewer lines or with fewer concepts?
- Is this abstraction used more than once (or about to be)?
- Would a staff engineer ask “why didn’t you just…?”

## Verification

- Behavior is unchanged (tests pass)
- The resulting code is easier to read and modify
