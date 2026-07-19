---
name: git-workflow-and-versioning
description: >
  Apply clean Git practices: atomic commits, meaningful messages, sensible branching, and safe history.
  Use when committing, branching, preparing PRs, or managing version history.
---

# Git Workflow and Versioning

## Overview

Clean history makes collaboration, debugging, and reverts much easier. Prefer small, focused commits with clear messages.

## When to Use

- Creating commits
- Preparing a pull request
- Branch management
- When history has become messy

## Core Practices

### Commits
- Atomic: one logical change per commit
- Message format (recommended):
  ```
  type: short summary in imperative mood

  Optional body explaining why, not just what.
  ```
  Common types: feat, fix, refactor, test, docs, chore, perf, ci

- Avoid: "fix stuff", "WIP", "updates", "misc"

### Branching
- Prefer short-lived feature branches
- Keep main/master releasable
- Rebase or merge according to team convention (be consistent)

### Pull Requests
- Small PRs are easier to review
- Description should explain *why* and how to test
- Link to issues or specs when relevant

### Safety
- Never force-push to shared main/master
- Prefer interactive rebase only on private branches
- Review the diff before committing

## Verification

- Commit messages are clear and accurate
- Diff matches the commit message
- History tells a coherent story of the work
