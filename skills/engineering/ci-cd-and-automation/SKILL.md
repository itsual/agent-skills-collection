---
name: ci-cd-and-automation
description: >
  Design and improve CI/CD pipelines, quality gates, and automation so that every change is validated consistently.
  Use when working on build pipelines, GitHub Actions, deployment automation, or developer experience tooling.
---

# CI/CD and Automation

## Overview

Reliable automation is what turns good local development into trustworthy delivery.

## When to Use

- Creating or modifying pipelines
- Adding quality gates (tests, lint, security scans)
- Improving developer feedback loops
- Deployment automation

## Principles

- Fast feedback on the most common failures
- Deterministic, hermetic builds where possible
- Fail closed on quality and security gates for main branches
- Keep pipelines readable and maintainable

## Common Stages

- Lint / static analysis
- Unit & integration tests
- Security / dependency scanning
- Build artifacts
- Deploy (with appropriate approvals/environments)

## Verification

- Pipeline correctly gates bad changes
- Happy path is reasonably fast
- Failures provide actionable signal
