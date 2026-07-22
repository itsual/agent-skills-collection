---
name: data-loss-prevention
description: >
  Design DLP controls that reduce sensitive data exfiltration — classification, policies, channels, and response — without crushing legitimate work.
  Use when protecting PII, secrets, or IP across email, endpoints, cloud storage, and web channels.
---

# Data Loss Prevention (DLP)

## Overview

DLP aims to stop sensitive data from leaving approved boundaries. Success depends on accurate classification, sensible policies, and tuning that users can live with.

## When to Use

- Protecting regulated or high-value data
- Email, endpoint, and cloud DLP deployments
- Insider risk and accidental exposure reduction
- Supporting privacy and IP protection programs

## Core Practices

- Classify data that truly needs DLP enforcement
- Start with monitoring/alerting before hard blocks where risk allows
- Cover high-risk channels first (email, USB, web upload, cloud sync)
- Tune to reduce false positives that drive shadow workarounds
- Define response for intentional vs accidental violations
- Combine DLP with access control and encryption — not as a standalone silver bullet

## Principles

- You cannot protect data you have not identified
- Over-blocking destroys trust and creates bypasses
- DLP is weaker against determined insiders with legitimate access — layer controls
- Privacy and employee monitoring ethics matter in design

## Verification

- [ ] Sensitive data classes are defined for DLP scope
- [ ] Policies are tuned with FP review
- [ ] Response process exists for violations
