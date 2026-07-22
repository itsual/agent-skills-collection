---
name: model-evaluation
description: >
  Evaluate models with appropriate metrics, validation schemes, baselines, and error analysis — not only a single leaderboard score.
  Use when comparing models, deciding ship/no-ship, or diagnosing failure modes.
---

# Model Evaluation

## Overview

Evaluation decides whether a model is good enough for the job. It requires the right metrics, honest validation design, and qualitative error analysis.

## When to Use

- Comparing candidate models
- Go/no-go for production
- Diagnosing systematic errors
- Monitoring offline vs online performance gaps

## Core Practices

- Select metrics aligned to business costs and decision type
- Use validation that matches data structure (k-fold, time-series split, grouped split)
- Always report strong simple baselines
- Perform error analysis by segment
- Check calibration when using probabilities
- Separate offline evaluation from online experiment results

## Principles

- A model that beats a weak baseline may still be useless
- Aggregate metrics hide segment failures
- Overfitting to the test set is still overfitting
- Evaluation code deserves the same care as training code

## Verification

- [ ] Metrics match the decision problem
- [ ] Validation scheme is justified
- [ ] Baselines and segment errors are reported
