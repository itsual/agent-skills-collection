---
name: database-migrations
description: >
  Design and apply safe, reversible (or explicitly one-way) database schema and data migrations with minimal downtime.
  Use when changing database structure or performing large data transformations.
---

# Database Migrations

## Overview

Schema and data changes are among the riskiest operations in production. Treat them with discipline.

## When to Use

- Adding, changing, or removing tables/columns/indexes
- Large data backfills or transformations
- Expanding or contracting multi-tenant schemas

## Core Practices

- Prefer expand → migrate → contract over destructive one-step changes
- Make migrations backward-compatible when zero-downtime is required
- Test migrations against realistic data volumes and production-like conditions
- Separate schema changes from large data backfills when possible
- Have a clear rollback or forward-fix strategy
- Monitor locks, replication lag, and performance during migration

## Principles

- Never assume a migration that worked on small data will work on large data
- Avoid long-running transactions that block production traffic
- Document non-obvious data transformations

## Verification

- Migration has been tested on a realistic copy of data
- Rollback or recovery path is known
- Application compatibility during the migration window is understood
