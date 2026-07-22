---
name: data-quality-monitoring
description: >
  Monitor data quality in pipelines and tables — freshness, completeness, volume, schema, and authenticity — with alerts and ownership.
  Use when preventing silent data breakage from corrupting dashboards and models.
---

# Data Quality Monitoring

## Overview

Data quality monitoring catches broken pipelines before executives and models do. Checks must be owned, actionable, and tuned to critical datasets.

## When to Use

- Warehouse and pipeline reliability
- Critical dashboard source protection
- ML training data assurance
- SLA definitions for data products

## Core Practices

- Define checks: freshness, row volume, null rates, uniqueness, schema drift
- Prioritize critical tables and columns first
- Alert to owners with enough context to debug
- Track incident history and recurring failure modes
- Gate downstream jobs on upstream quality when appropriate
- Document expected ranges and business rules

## Principles

- Silent failure is worse than loud failure
- Not every table needs the same rigor
- Quality is a product feature of data platforms
- Ownership beats orphaned alerts

## Verification

- [ ] Critical datasets have automated checks
- [ ] Alerts reach accountable owners
- [ ] Recurring breaks drive root-cause fixes
