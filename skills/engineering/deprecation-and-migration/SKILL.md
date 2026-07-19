---
name: deprecation-and-migration
description: >
  Safely retire old systems, APIs, or code paths and migrate users or callers with minimal disruption.
  Use when removing features, changing contracts, upgrading major dependencies, or sunsetting services.
---

# Deprecation and Migration

## Overview

Removing things is often harder than adding them. Do it deliberately with communication, dual-running, and clear timelines.

## When to Use

- Deprecating an API, feature, or configuration
- Major version upgrades with breaking changes
- Migrating data or traffic from an old system to a new one
- Cleaning up legacy code paths that still have callers

## Core Process

1. **Inventory** – Who/what still depends on the old path?
2. **Announce** – Communicate deprecation with timeline and migration guide.
3. **Dual-run** – Support both old and new during a transition window when possible.
4. **Migrate** – Provide tools, docs, or automated migration where feasible.
5. **Monitor** – Track remaining usage of the old path.
6. **Remove** – Only after usage is near zero or the deadline is enforced.
7. **Clean up** – Delete code, docs, and feature flags related to the old path.

## Principles

- Prefer soft deprecation + warnings before hard removal
- Make the new path strictly better or clearly necessary
- Automate migration when the cost is justified
- Never surprise production users with sudden breakage

## Verification

- Migration path is documented and tested
- Remaining usage is measurable
- Rollback or extension of the timeline is possible if needed
