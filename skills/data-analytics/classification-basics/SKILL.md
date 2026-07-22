---
name: classification-basics
description: >
  Build and evaluate classification models — class balance, metrics (precision/recall/ROC), thresholds, and error costs.
  Use when predicting categories such as churn, fraud, conversion, or risk tiers.
---

# Classification Basics

## Overview

Classification predicts discrete labels. Success depends on metric choice aligned to business costs, not only accuracy on imbalanced data.

## When to Use

- Churn, conversion, fraud, and risk classification
- Lead scoring and propensity models
- Choosing thresholds for operational decisions
- Comparing classification algorithms baseline-to-baseline

## Core Practices

- Inspect class balance and cost of error types
- Choose metrics that match the decision (precision, recall, F1, AUC, etc.)
- Use proper train/validation/test splits (and time-based splits when needed)
- Calibrate probabilities if decisions use scores
- Set thresholds from cost/benefit, not default 0.5
- Monitor drift after deployment

## Principles

- 99% accuracy can be useless on 1% positive class
- False positives and false negatives have different prices
- Leakage from future data invalidates results
- Interpretability may be required in regulated settings

## Verification

- [ ] Metrics match business error costs
- [ ] Evaluation method avoids leakage
- [ ] Threshold rationale is documented
