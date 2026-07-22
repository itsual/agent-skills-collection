---
name: data-quality-management
description: >
  Manage data quality end-to-end — dimensions, rules, remediation, and prevention — beyond one-off cleaning scripts.
  Use when building sustained data quality programs or fixing systemic accuracy, completeness, or consistency problems.
---

# Data Quality Management

## Overview

Data quality management treats quality as an ongoing product property: define what “good” means, measure it, fix root causes, and prevent recurrence.

## When to Use

- Chronic dashboard or model distrust
- Regulatory or financial data accuracy requirements
- Scaling data products beyond hero analysts
- Defining SLAs for critical tables

## Core Practices

- Define quality dimensions: accuracy, completeness, consistency, timeliness, uniqueness, validity
- Set rules and thresholds per critical field/table
- Measure continuously; publish quality scores where useful
- Triage incidents: severity, owner, SLA
- Fix upstream root causes, not only downstream patches
- Prevent via contracts, validation at entry, and producer accountability

## Principles

- Quality is defined relative to purpose — bank-grade ≠ blog-grade
- Detection without remediation is noise
- Producers must own quality of what they emit
- Perfect quality on unimportant data is waste

## Verification

- [ ] Critical data has explicit quality rules
- [ ] Incidents have owners and closure tracking
- [ ] Upstream fixes are preferred over perpetual cleanup
