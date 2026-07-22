---
name: experiment-analysis
description: >
  Analyze experiments and A/B tests with proper metrics, statistics, and decision rules — avoiding common pitfalls that create false wins.
  Use when evaluating online experiments, product tests, or controlled trials for decision-making.
---

# Experiment Analysis

## Overview

Experiment analysis determines whether an intervention caused a change. Credible analysis needs pre-defined metrics, adequate power, and resistance to peeking and p-hacking.

## When to Use

- A/B and multivariate test readouts
- Product feature experiments
- Growth and pricing tests
- Program evaluations with treatment/control

## Core Practices

- Lock primary metric and stopping rules before reading results
- Check randomization balance and data quality first
- Estimate effects with uncertainty (intervals), not only p-values
- Guard against multiple comparisons and optional stopping
- Segment carefully; treat exploratory cuts as exploratory
- Document decision: ship, iterate, or abandon

## Principles

- Statistical significance ≠ practical significance
- Underpowered tests waste time and create noise
- SRM (sample ratio mismatch) is a red flag — investigate
- Novelty and primacy effects can mislead short tests

## Verification

- [ ] Primary metric was pre-specified
- [ ] Data quality and assignment checks passed
- [ ] Decision accounts for effect size and uncertainty
