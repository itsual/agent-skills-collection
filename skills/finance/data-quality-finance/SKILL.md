---
name: data-quality-finance
description: >
  Improve financial data quality — definitions, lineage, reconciliations, and ownership — so reporting and models are trustworthy.
  Use when numbers conflict across systems, metrics are disputed, or automation is blocked by bad data.
---

# Data Quality (Finance)

## Overview

Finance decisions inherit data quality. Conflicting metrics, broken reconciliations, and unclear ownership create noise and politics.

## When to Use

- Conflicting reports from different systems
- Metric definition disputes
- Pre-automation data cleanup
- Audit findings on data integrity

## Core Practices

- Define canonical sources for key metrics
- Document data lineage for material reports
- Reconcile critical subledgers to GL on a cadence
- Assign data owners for master data domains
- Fix root causes, not only report patches

## Principles

- One source of truth per metric where possible
- Manual journal adjustments that “fix” reports are a smell
- Quality is a process, not a one-time cleanse
- Incentives to game metrics will surface in the data

## Verification

- [ ] Critical metrics have canonical definitions and sources
- [ ] Material reconciliations are routine
- [ ] Data issues have owners and remediation paths
