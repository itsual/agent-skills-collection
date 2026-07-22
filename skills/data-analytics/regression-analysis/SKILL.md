---
name: regression-analysis
description: >
  Build and interpret regression models for explanation and prediction — with diagnostics, assumptions, and honest communication of limits.
  Use when modeling relationships between variables or creating baseline predictive models.
---

# Regression Analysis

## Overview

Regression relates outcomes to predictors. It is a workhorse for both explanation and prediction when assumptions are checked and results are interpreted carefully.

## When to Use

- Estimating associations with controls
- Baseline predictive models
- Understanding driver importance (with caution)
- Forecasting with regression-based approaches

## Core Practices

- Specify the model to match the question (linear, logistic, etc.)
- Check residuals, leverage, multicollinearity, and fit diagnostics
- Transform or specify nonlinearities when needed
- Avoid interpreting coefficients causally without design support
- Validate predictive performance out of sample
- Report uncertainty and model limitations

## Principles

- Correlation still isn’t causation inside a regression
- Overfitting glamorous in-sample fits
- Omitted variables can bias coefficients badly
- Simpler interpretable models are often preferable for decisions

## Verification

- [ ] Model form matches outcome type
- [ ] Diagnostics were inspected
- [ ] Predictive claims use held-out evaluation
