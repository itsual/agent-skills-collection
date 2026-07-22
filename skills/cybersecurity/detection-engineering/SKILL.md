---
name: detection-engineering
description: >
  Engineer security detections — high-signal rules, telemetry requirements, testing, and tuning — as a product for responders.
  Use when building SIEM/EDR detections or reducing false positive load while improving true positive coverage.
---

# Detection Engineering

## Overview

Detection engineering treats alerts as a product: defined threat coverage, quality telemetry, tested logic, and continuous tuning based on analyst feedback.

## When to Use

- Creating new SIEM/EDR detections
- Reducing noisy alert queues
- Mapping detections to threat techniques
- Operationalizing threat intel into alerts

## Core Practices

- Start from threats/TTPs, not only available logs
- Specify required telemetry and normalize fields
- Write detections with clear triage guidance
- Test against positive and negative cases
- Tune using false positive feedback loops
- Version and review detection-as-code where possible

## Principles

- An unmaintainable rule is a future outage or missed detection
- Context in the alert reduces mean time to understand
- Coverage metrics should track real techniques, not rule counts
- Suppression without root-cause analysis hides problems

## Verification

- [ ] Detections map to explicit threats/TTPs
- [ ] Triage notes exist for responders
- [ ] FP rates are monitored and tuned
