---
name: hypothesis-testing
description: >
  Design and interpret hypothesis tests correctly — hypotheses, error types, p-values, power, and multiple comparisons.
  Use when formally testing differences or effects and communicating results without common statistical fallacies.
---

# Hypothesis Testing

## Overview

Hypothesis testing provides a framework for assessing evidence against a null model. Misuse of p-values and multiple testing is widespread — discipline matters.

## When to Use

- A/B test and experiment readouts
- Formal comparison of groups or periods
- Validating whether an observed difference is plausible under noise
- Pre-registering analysis plans

## Core Practices

- State null and alternative hypotheses clearly
- Choose tests appropriate to data type and design
- Consider power and minimum detectable effect before concluding “no effect”
- Control or account for multiple comparisons when exploring many tests
- Report effect sizes and intervals, not only p-values
- Pre-specify primary tests when decisions depend on them

## Principles

- p > 0.05 is not proof of no difference
- p-hacking and HARKing invalidate inference
- Practical significance can matter more than statistical significance
- Design (randomization, sampling) grounds interpretation

## Verification

- [ ] Hypotheses and primary test are explicit
- [ ] Multiple-testing risk is addressed if applicable
- [ ] Interpretation avoids common fallacies
