---
name: sql-for-analysis
description: >
  Write analytical SQL that is correct, readable, and performant — joins, window functions, aggregations, and reusable query patterns.
  Use when analyzing data in warehouses, building datasets, or reviewing analytical queries.
---

# SQL for Analysis

## Overview

Analytical SQL is how most business data work gets done. Clarity, correctness of grain, and sensible performance matter more than clever tricks.

## When to Use

- Ad-hoc analysis in the warehouse
- Building clean datasets for BI or models
- Code review of analytical queries
- Teaching analysts stronger SQL patterns

## Core Practices

- Be explicit about grain (what does one row mean?)
- Use window functions for running totals, ranks, lags
- Prefer readable CTEs over nested chaos where it helps
- Filter early; aggregate deliberately
- Validate row counts and totals after joins
- Watch for fan-out joins that explode rows silently

## Principles

- Wrong grain is the most common serious SQL bug
- NULL handling must be intentional
- Performance starts with understanding table size and keys
- Reproducible saved queries beat one-off editor history

## Verification

- [ ] Grain is stated and checked
- [ ] Joins are validated for fan-out
- [ ] Results match known control totals where available
