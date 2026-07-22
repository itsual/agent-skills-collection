---
name: adversary-emulation
description: >
  Plan and run adversary emulation — CTI-driven scenarios mapped to MITRE ATT&CK TTPs, executed under controls, and measured for prevention and detection outcomes.
  Use when testing defenses against specific threat actors or technique chains rather than generic vulnerability hunting.
---

# Adversary Emulation

## Overview

Adversary emulation is intelligence-led red teaming: replicate the tactics, techniques, and procedures of relevant threat actors to test whether defenses stop, detect, and respond to *those* behaviors.

## When to Use

- CTI-informed offensive exercises
- Validating detections against known actor tradecraft
- Building ATT&CK-aligned emulation plans
- Bridging threat intel and security operations

## Core Practices

- Select adversaries relevant to your sector, tech, and threat model
- Extract TTPs from credible intel; map to MITRE ATT&CK
- Build an ordered emulation plan (attack chain), not a random technique list
- Prepare tools/procedures that approximate behaviors within legal and safety limits
- Execute under approved Rules of Engagement
- Record which steps were prevented, detected, alerted, and responded to
- Convert gaps into detection engineering and control backlog items

## Principles

- Emulation without CTI is just creative pen testing
- Perfect malware clones are unnecessary — faithful *behaviors* matter
- Measurement of blue outcomes is the point, not red “wins”
- Re-run emulations after fixes to prove improvement

## Verification

- [ ] Scenario is tied to documented threat intelligence
- [ ] TTPs are mapped to ATT&CK (or equivalent)
- [ ] Prevention/detection/response results are captured per step
