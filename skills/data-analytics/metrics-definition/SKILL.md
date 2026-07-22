---
name: metrics-definition
description: >
  Define business and product metrics with precise formulas, owners, grain, and caveats so everyone calculates the same truth.
  Use when creating metric dictionaries, resolving conflicting numbers, or instrumenting analytics.
---

# Metrics Definition

## Overview

Metrics only work when defined. Ambiguous metrics create conflicting dashboards, political arguments, and bad decisions.

## When to Use

- Building a metrics dictionary / source of truth
- Resolving “why don’t these two numbers match?”
- Instrumenting new product or business metrics
- Aligning Finance, Product, and Data definitions

## Core Practices

- Write formula, filters, grain (user/day/account), and time zone
- Name owners and source systems
- Document known edge cases and exclusions
- Version definitions when they change
- Validate new metrics against manual samples
- Prefer stable definitions over frequent renorming

## Principles

- If two teams disagree on a number, check definitions first
- Changing a metric definition breaks trend history — note it
- Proxy metrics need explicit linkage to the real goal
- Goodhart’s law: metrics under pressure distort behavior

## Verification

- [ ] Critical metrics have written definitions
- [ ] Owners and sources are clear
- [ ] Conflicts are resolvable via the dictionary
