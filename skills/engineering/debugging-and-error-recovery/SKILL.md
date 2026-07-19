---
name: debugging-and-error-recovery
description: >
  Systematically reproduce, localize, fix, and guard against bugs and errors.
  Use whenever something is broken, tests are failing, unexpected behavior occurs, or the user reports a bug.
---

# Debugging and Error Recovery

## Overview

Effective debugging is a disciplined process, not random changes. Reproduce first, then localize, then fix, then prevent recurrence.

## When to Use

- Failing tests
- Runtime errors or exceptions
- Unexpected behavior reported by users or observed in logs
- Regressions after a change

## Core Process

### 1. Reproduce
Create a reliable, minimal reproduction. If you cannot reproduce it, you cannot confidently fix it.

### 2. Localize
Narrow down where the failure occurs. Use:
- Stack traces
- Logs
- Bisecting recent changes
- Targeted tests or print/debugger statements

### 3. Understand Root Cause
Do not stop at the symptom. Ask why the failure happened.

### 4. Fix
Make the smallest correct change that addresses the root cause.

### 5. Guard
Add or improve a test that would have caught this issue. Consider additional defensive checks if appropriate.

## Principles

- Change one thing at a time when hypothesizing
- Prefer evidence over guesses
- Keep the failing test (or reproduction) while fixing
- Avoid “drive-by” refactors during a debug session

## Verification

- Original reproduction now passes
- New or improved test covers the case
- Related existing tests still pass
- No new symptoms introduced
