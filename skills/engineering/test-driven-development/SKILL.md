---
name: test-driven-development
description: >
  Write failing tests first, then implement the minimum code to make them pass.
  Use for new features, bug fixes, and when high confidence in correctness is required.
  Trigger on requests involving tests, TDD, test coverage, or "write tests for".
---

# Test-Driven Development

## Overview

TDD produces better design and higher confidence. The red → green → refactor cycle is the core discipline.

## When to Use

- Implementing new behavior
- Fixing bugs (write the failing test that reproduces the bug first)
- When correctness matters more than speed of initial implementation
- Refactoring existing code (characterization tests first if needed)

## Core Cycle

1. **Red** – Write a small failing test that describes the desired behavior.
2. **Green** – Write the simplest code that makes the test pass.
3. **Refactor** – Clean up while keeping tests green.

Repeat in small increments.

## Guidelines

- Test behavior, not implementation details
- One logical assertion focus per test when practical
- Use descriptive test names that explain the scenario and expected outcome
- Prefer fast, deterministic unit tests; add integration/E2E where they add unique value
- For bug fixes: always start with a test that fails on the current code

## What Makes a Good Test

- Fails for the right reason
- Readable by a future reader
- Independent of other tests
- Fast enough to run frequently

## Common Pitfalls

- Writing tests after the code (misses the design feedback of TDD)
- Testing private methods directly
- Over-mocking (tests become brittle and low-value)
- Large tests that check too many things at once

## Verification

- All new tests fail before the implementation is added
- All tests pass after implementation
- Edge cases and error paths have coverage
- Tests remain valuable after future refactors
