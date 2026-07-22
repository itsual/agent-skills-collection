---
name: analytics-engineering
description: >
  Practice analytics engineering — reliable, tested, versioned data transformations that turn raw sources into trustworthy analytical tables.
  Use when building dbt-style models, curated marts, or the semantic layer between raw data and BI.
---

# Analytics Engineering

## Overview

Analytics engineering applies software engineering discipline to analytical data transformation: modular SQL/models, tests, documentation, and CI.

## When to Use

- Building curated warehouse marts
- Replacing fragile spreadsheet pipelines
- Creating shared metrics tables for BI
- Scaling analyst work beyond one-off queries

## Core Practices

- Model in layers (staging → intermediate → marts)
- Test assumptions (unique, not_null, relationships)
- Document models and columns for consumers
- Version control all transformations
- Use CI to catch breaking changes
- Define clear contracts with data producers and consumers

## Principles

- One trusted mart beats ten conflicting extracts
- Tests encode business rules
- Analytics code deserves code review
- Change management protects downstream users

## Verification

- [ ] Models are layered and tested
- [ ] Documentation is discoverable
- [ ] Changes go through version control / CI
