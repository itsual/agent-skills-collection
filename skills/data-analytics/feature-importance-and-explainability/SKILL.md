---
name: feature-importance-and-explainability
description: >
  Explain model behavior using appropriate importance and interpretability methods — with caution about what explanations can and cannot claim.
  Use when stakeholders need to understand drivers, debug models, or meet transparency expectations.
---

# Feature Importance and Explainability

## Overview

Explainability tools help humans understand model behavior. They are approximations and diagnostic aids — not automatic causal truth.

## When to Use

- Debugging unexpected model behavior
- Stakeholder communication about drivers
- Regulatory or policy transparency needs
- Feature selection hypotheses

## Core Practices

- Choose methods fit for model type (linear coeffs, permutation importance, SHAP, etc.)
- Prefer global + local explanations when both matter
- Validate explanations against domain knowledge and stability
- Avoid implying causality from importance rankings alone
- Document explanation method limitations
- For high-stakes decisions, prioritize inherently interpretable models when possible

## Principles

- Explanation ≠ causation
- Unstable explanations undermine trust
- Stakeholders need actionable narratives, not only plots
- Transparency requirements may dictate method choice

## Verification

- [ ] Method choice is justified for the model
- [ ] Limitations are communicated
- [ ] Explanations were sense-checked with domain experts
