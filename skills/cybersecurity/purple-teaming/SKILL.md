---
name: purple-teaming
description: >
  Run purple team exercises where offense and defense collaborate to improve detections, controls, and response in tight feedback loops.
  Use when bridging red/blue gaps or rapidly raising detection coverage for known TTPs.
---

# Purple Teaming

## Overview

Purple teaming is structured collaboration: emulate a technique, observe detection gaps, improve alerts and controls, and retest — iteratively.

## When to Use

- Improving SOC detection coverage
- After red team findings to institutionalize lessons
- Mapping controls to MITRE ATT&CK-style techniques
- Building repeatable detection engineering loops

## Core Practices

- Pick a technique/TTP and success criteria for detection
- Execute safely in agreed scope
- Observe what was logged, alerted, and missed
- Improve telemetry, rules, or controls immediately where possible
- Retest to confirm improvement
- Document coverage gains over time

## Principles

- Collaboration beats adversarial theater for capability building
- Small frequent exercises outperform rare large spectacles
- Coverage maps should be honest about blind spots
- Automation of retests maintains gains

## Verification

- [ ] Exercises have explicit TTPs and detection goals
- [ ] Gaps produce concrete detection/control changes
- [ ] Retests confirm improvement
