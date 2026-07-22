---
name: causal-inference-basics
description: >
  Apply causal inference basics — potential outcomes mindset, confounding, and credible designs — when estimating effects from observational or experimental data.
  Use when asked “did X cause Y?” and simple correlation is not enough.
---

# Causal Inference Basics

## Overview

Causal inference estimates what would happen under intervention. Without a credible design, observational associations are easily confounded.

## When to Use

- Estimating impact of a program, feature, or policy
- When randomized experiments are partial or unavailable
- Critiquing causal claims in analyses
- Choosing between experiment and quasi-experimental approaches

## Core Practices

- State the causal question and target population clearly
- Draw assumptions (confounders, selection) explicitly
- Prefer experiments when feasible
- Consider designs: matching, difference-in-differences, IV, RDD — only with justified assumptions
- Run sensitivity checks for unobserved confounding
- Report estimates with assumptions, not only point numbers

## Principles

- No causes in, no causes out
- Adjustment for post-treatment variables can bias effects
- A pretty DAG does not prove assumptions hold
- Humility about causal claims is a professional virtue

## Verification

- [ ] Causal question is explicit
- [ ] Identifying assumptions are stated
- [ ] Robustness / sensitivity checks are present
