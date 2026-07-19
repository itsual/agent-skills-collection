---
name: incremental-implementation
description: >
  Implement features in thin, end-to-end vertical slices that can be verified independently.
  Use when building new functionality, especially larger features. Prefer this over big-bang implementation.
---

# Incremental Implementation

## Overview

Build in small, complete slices rather than large unfinished layers. Each slice should deliver a thin but working piece of value and be verifiable.

## When to Use

- Implementing any non-trivial feature
- When previous large attempts have stalled or produced hard-to-debug code
- When working with an agent that benefits from frequent feedback loops

## Core Process

1. **Identify the thinnest useful slice** that touches the full path (UI → logic → data, or API → service → storage).
2. **Implement only that slice**.
3. **Verify it works** (tests + manual/runtime check).
4. **Expand** to the next slice.
5. Refactor as needed while staying green.

## Principles

- Prefer vertical slices over horizontal layers early on
- Keep the system in a working state as much as possible
- Make the first slice intentionally small to validate direction
- Resist adding “while I’m here” improvements outside the current slice

## Anti-Patterns

- Building all the models first, then all the services, then the UI
- Large uncommitted or untested changes
- Scope expansion during a slice

## Verification

After each slice:
- Relevant tests pass
- The slice is demonstrably working end-to-end
- No obvious regressions in existing behavior
