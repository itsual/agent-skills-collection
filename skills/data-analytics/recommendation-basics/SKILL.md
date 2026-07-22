---
name: recommendation-basics
description: >
  Build basic recommendation approaches — collaborative filtering, content-based methods, and evaluation — with awareness of bias and feedback loops.
  Use when personalizing content, products, or next-best-actions with data.
---

# Recommendation Basics

## Overview

Recommenders rank items for users. Offline metrics, online experiments, and feedback-loop awareness are all required for systems that improve rather than collapse into popularity traps.

## When to Use

- Product or content recommendations
- Next-best-action ranking
- Personalized ranking features
- Evaluating recommender quality

## Core Practices

- Define the recommendation objective (engagement, revenue, satisfaction)
- Start with simple popularity and co-occurrence baselines
- Evaluate with ranking metrics and business outcomes
- Address cold-start for new users/items
- Monitor diversity, popularity bias, and feedback loops
- Validate online with experiments when stakes warrant

## Principles

- Offline accuracy ≠ online value always
- Feedback loops can amplify bias
- Diversity and fairness may be explicit goals
- Explainability helps user trust in some domains

## Verification

- [ ] Objective and metrics are explicit
- [ ] Baselines are reported
- [ ] Bias/loop risks are considered
