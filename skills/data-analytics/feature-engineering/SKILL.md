---
name: feature-engineering
description: >
  Create features that improve model signal — transformations, encodings, aggregates, and leakage-safe pipelines.
  Use when preparing inputs for machine learning models or improving predictive performance thoughtfully.
---

# Feature Engineering

## Overview

Feature engineering turns raw fields into predictive signal. It is often higher leverage than swapping algorithms — and a primary source of leakage risk.

## When to Use

- Building ML training datasets
- Improving underperforming models
- Encoding categoricals, text, and time effects
- Creating behavioral aggregates (counts, recency, frequency)

## Core Practices

- Engineer features from domain hypotheses, not only brute force
- Prevent leakage (no future information in past rows)
- Encode categoricals appropriately (one-hot, target, embeddings — with care)
- Aggregate with clear time windows aligned to prediction time
- Scale/normalize when the model class requires it
- Track feature definitions for production parity

## Principles

- Leakage creates models that look brilliant and fail in production
- More features ≠ better generalization
- Training-serving skew destroys deployed performance
- Simple interpretable features aid debugging and trust

## Verification

- [ ] Point-in-time correctness is enforced
- [ ] Feature definitions are documented
- [ ] Train/serve parity plan exists for deployed models
