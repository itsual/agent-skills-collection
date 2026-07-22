---
name: customer-health-scores
description: >
  Design and operate customer health scores that combine product usage, relationship, and outcome signals into actionable risk and opportunity views.
  Use when building health models, risk dashboards, or prioritization systems for CS teams.
---

# Customer Health Scores

## Overview

Health scores summarize whether a customer is likely to stay, grow, or churn. They are useful only when predictive, explainable, and tied to interventions.

## When to Use

- Building or recalibrating health scoring
- Portfolio prioritization for CSMs
- Executive retention risk reporting
- Triggering plays based on health changes

## Core Practices

- Combine multiple signal types (usage, support, sentiment, commercial)
- Weight signals based on correlation with retention outcomes
- Make scores explainable (why is this account yellow?)
- Define actions by health band — not only colors
- Review model performance vs actual churn/expansion
- Avoid false precision; bands often beat 0–100 theater

## Principles

- A score without a playbook is a vanity metric
- Lagging signals alone are too late
- Product usage without outcome context can mislead
- Human override should be possible and audited

## Verification

- [ ] Score components and weights are documented
- [ ] Health changes trigger defined workflows
- [ ] Score predicts outcomes better than chance/history
