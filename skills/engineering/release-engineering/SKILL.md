---
name: release-engineering
description: >
  Design reliable release processes including versioning, changelogs, release notes, artifacts, and promotion across environments.
  Use when improving how software is packaged, versioned, and released to users or production.
---

# Release Engineering

## Overview

Release engineering turns working code into safely deliverable artifacts and communicates changes clearly.

## When to Use

- Setting up or improving release processes
- Creating versioning and changelog standards
- Preparing major or customer-facing releases

## Key Practices

- Semantic versioning (or clear alternative) with documented rules
- Automated changelog / release notes generation where possible
- Reproducible builds and immutable artifacts
- Promotion model (dev → staging → prod) with appropriate gates
- Clear ownership of the release process
- Rollback or hotfix paths defined in advance

## Principles

- Make the happy-path release boring and automated
- Optimize for safety and recoverability over pure speed
- Communicate breaking changes and migration steps explicitly

## Verification

- Releases are repeatable and mostly automated
- Artifacts are traceable to source and build inputs
- Stakeholders know what changed and how to react
