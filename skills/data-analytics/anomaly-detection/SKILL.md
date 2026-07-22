---
name: anomaly-detection
description: >
  Detect anomalies in metrics and datasets — defining “normal,” reducing false alarms, and routing true issues to investigation.
  Use when building alerting on KPIs, fraud-like outliers, or data quality anomaly checks.
---

# Anomaly Detection

## Overview

Anomaly detection finds rare deviations from expected patterns. The hard part is defining expected behavior and keeping alert volume actionable.

## When to Use

- KPI and system metric alerting
- Fraud and abuse candidate detection
- Data quality monitoring
- Operational incident early warning

## Core Practices

- Define normal with seasonality and known events in mind
- Choose methods fit for volume and pattern type (statistical, ML, rules)
- Tune sensitivity to balance misses vs alert fatigue
- Enrich alerts with context for faster triage
- Close the loop: label true/false positives to improve
- Separate data bugs from real-world anomalies when possible

## Principles

- Alert fatigue disables the system
- Context turns anomalies into diagnoses
- Supervised approaches need ongoing labels
- Not every spike is actionable — prioritization matters

## Verification

- [ ] Expected baseline accounts for seasonality/events
- [ ] Alert volume is sustainable for responders
- [ ] Feedback loop exists for tuning
