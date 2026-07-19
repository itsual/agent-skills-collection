---
name: feature-flag-architecture
description: >
  Design and operate feature flags for safe rollouts, experimentation, and operational control.
  Use when introducing gradual releases, A/B tests, kill switches, or long-lived configuration toggles.
---

# Feature Flag Architecture

## Overview

Feature flags decouple deployment from release and enable safer delivery. They also add complexity and must be managed deliberately.

## When to Use

- Gradual or percentage rollouts
- Experiments and A/B tests
- Kill switches for risky features
- Trunk-based development with incomplete features

## Design Principles

- Short-lived flags are preferable to permanent ones
- Name flags clearly and include ownership/expiry information
- Avoid flag dependency spaghetti
- Clean up flags after full rollout or experiment conclusion
- Consider performance and consistency implications of flag evaluation

## Operational Checklist

- [ ] Flag has a clear owner and expected lifetime
- [ ] Default value is safe
- [ ] Monitoring exists for the new behavior
- [ ] Removal plan exists
- [ ] Evaluation points are consistent (especially in distributed systems)

## Verification

- Flags can be toggled without redeploying (where intended)
- Stale flags are tracked and removed
- Experiments have clear success metrics and end conditions
