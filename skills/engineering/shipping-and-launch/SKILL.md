---
name: shipping-and-launch
description: >
  Prepare and execute safe releases with checklists for monitoring, rollback, and communication.
  Use when deploying to production, launching a feature, or preparing a release.
---

# Shipping and Launch

## Overview

Shipping is a distinct skill from building. Reduce risk with preparation and clear rollback paths.

## When to Use

- Before production deploys
- Feature launches
- Major version releases

## Pre-Launch Checklist

- [ ] Tests and CI green
- [ ] Feature flags or gradual rollout considered
- [ ] Monitoring and alerts in place for the new paths
- [ ] Rollback plan is known and tested if possible
- [ ] Documentation / release notes updated
- [ ] Stakeholders informed

## During / After Launch

- Watch key metrics and error rates
- Be ready to roll back or disable via flag
- Capture issues for rapid follow-up

## Verification

- Launch criteria met
- Observability covers the change
- Rollback path is viable
