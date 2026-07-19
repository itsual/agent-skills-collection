---
name: testing-strategy
description: >
  Define a balanced testing strategy across unit, integration, contract, and end-to-end tests.
  Use when setting up test approach for a project, reviewing test quality, or deciding what kinds of tests to write.
---

# Testing Strategy

## Overview

Not every test provides equal value. A good strategy maximizes confidence per unit of effort and keeps the suite fast and reliable.

## When to Use

- Starting a new project or major component
- Reviewing an existing test suite that is slow, flaky, or low-value
- Deciding the right level of testing for a change

## Test Pyramid / Trophy Guidance

- Many fast, focused unit tests for domain logic and pure functions
- Fewer integration tests for critical boundaries (DB, external services)
- Selective end-to-end / browser tests for the most important user journeys
- Contract tests when multiple teams or services share interfaces

## Principles

- Test behavior and outcomes more than implementation details
- Optimize for quick feedback on the most common failures
- Treat flakiness as a high-priority bug
- Make test failures diagnostic

## Verification

- Critical paths have appropriate coverage at the right level
- The suite is fast enough to run frequently
- Flaky tests are actively managed
