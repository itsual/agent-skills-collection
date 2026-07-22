---
name: experiment-design-data
description: >
  Design experiments and A/B tests for causal learning — randomization, metrics, sample size, and guardrails.
  Use when planning product, growth, or policy experiments that will be analyzed with data.
---

# Experiment Design (Data)

## Overview

Experiment design creates the conditions for credible causal inference. Poor design cannot be rescued by sophisticated post-hoc analysis.

## When to Use

- Planning A/B or multivariate tests
- Policy or program pilots with treatment/control
- Estimating required sample size / runtime
- Defining metrics and guardrails before launch

## Core Practices

- Define primary metric and guardrail metrics up front
- Randomize at the right unit (user, account, geo)
- Estimate power / MDE and practical runtime
- Avoid contamination and interference between units
- Plan for SRM checks and data quality monitoring
- Pre-commit analysis methods where decisions are binding

## Principles

- Peeking without correction inflates false positives
- Underpowered tests waste time and create noise
- Novelty effects can mislead short experiments
- Ethics and user impact are part of design

## Verification

- [ ] Primary metric and hypotheses are pre-specified
- [ ] Sample size / runtime rationale exists
- [ ] Guardrails and stop rules are defined
