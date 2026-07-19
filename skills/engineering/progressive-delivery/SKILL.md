---
name: progressive-delivery
description: >
  Release changes safely using progressive delivery techniques (canaries, progressive rollouts, feature flags, A/B testing).
  Use when deploying risky changes or when you want fast feedback with limited blast radius.
---

# Progressive Delivery

## Overview

Progressive delivery reduces the risk of releases by gradually exposing changes and observing their impact before full rollout.

## When to Use

- High-risk or high-impact changes
- Continuous delivery environments
- Experiments and controlled rollouts

## Techniques

- Feature flags / toggles
- Canary releases
- Percentage / ring-based rollouts
- A/B testing and experimentation platforms
- Automated analysis of metrics during rollout (and automatic rollback when possible)

## Principles

- Decouple deployment from release
- Make rollback (or disable) fast and low-drama
- Observe the right metrics during progressive exposure
- Clean up flags and temporary rollout configuration afterward

## Verification

- Blast radius of a bad change is limited by default
- Rollout health is observable
- Rollback/disable path is known and tested
