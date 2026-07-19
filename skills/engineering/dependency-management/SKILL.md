---
name: dependency-management
description: >
  Manage third-party dependencies safely: minimize surface area, keep lockfiles honest, audit regularly, and upgrade deliberately.
  Use when adding, updating, or reviewing dependencies, or when addressing vulnerability reports.
---

# Dependency Management

## Overview

Every dependency is a liability as well as an asset. Treat the dependency graph with care.

## When to Use

- Adding a new library
- Upgrading dependencies
- Responding to security advisories
- Reviewing the overall dependency footprint

## Core Practices

- Prefer standard library or existing internal utilities when sufficient
- Check maintenance status, popularity, and known vulnerabilities before adding
- Always commit and review the lockfile
- Upgrade one dependency (or a small related group) at a time
- Read changelogs for non-trivial upgrades
- Run the test suite after upgrades

## Red Flags

- Large numbers of transitive dependencies for a small benefit
- Unmaintained packages
- Overly broad version ranges without a lockfile
- Bulk "bump everything" PRs without review

## Verification

- Lockfile is committed and up to date
- New dependencies have a clear justification
- Known high-severity vulnerabilities are addressed or explicitly accepted
