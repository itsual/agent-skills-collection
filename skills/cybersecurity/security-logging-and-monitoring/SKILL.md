---
name: security-logging-and-monitoring
description: >
  Design security logging and monitoring so attacks and misuse produce detectable, actionable signals without drowning responders in noise.
  Use when building detection capability, SIEM use cases, or improving visibility for incident response.
---

# Security Logging and Monitoring

## Overview

You cannot respond to what you cannot see. Security logging captures the right events; monitoring turns them into detections and alerts worth human time.

## When to Use

- SIEM/detection engineering
- Defining mandatory audit logs for critical systems
- Improving MTTD for identity and app abuse
- Meeting compliance logging requirements with operational value

## Core Practices

- Log authentication, authorization failures, admin actions, and data access for sensitive systems
- Ensure time sync, retention, and integrity of security logs
- Build detections from threat scenarios, not only compliance checklists
- Tune to reduce false positives; measure alert quality
- Protect logs from tampering and unauthorized access
- Define on-call response expectations per alert class

## Principles

- Logging everything is not the same as detecting anything
- Alerts without owners become ignored wallpaper
- Retention must match investigation and legal needs
- Privacy constraints still apply to security telemetry design

## Verification

- [ ] Critical systems emit required security events
- [ ] High-value detections exist and are tuned
- [ ] Alert response ownership is clear
