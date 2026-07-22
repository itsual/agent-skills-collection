---
name: rules-of-engagement
description: >
  Design and enforce Rules of Engagement (RoE) for offensive security tests — scope, allowed TTPs, safety stops, deconfliction, and legal authority.
  Use before any red team, adversary emulation, or high-impact offensive exercise.
---

# Rules of Engagement

## Overview

Rules of Engagement are the binding constraints that keep offensive testing lawful, safe, and aligned to objectives. No technical activity should start without approved RoE.

## When to Use

- Scoping red team or adversary emulation engagements
- Defining safe boundaries for social engineering or physical tests
- Establishing emergency stop and escalation paths
- Deconflicting offensive activity with SOC/IR

## Core Practices

- Document in-scope and out-of-scope systems, data, people, and locations
- Explicitly allow or forbid tactic classes (phishing, DoS, physical, destructive actions)
- Define objectives/flags and success criteria
- Set time windows, blackout periods, and rate limits where needed
- Name emergency contacts and kill-switch authority
- Define deconfliction process (how defenders recognize authorized testing when applicable)
- Specify data handling, evidence retention, and disclosure rules
- Obtain written approval from authorized stakeholders before start

## Principles

- RoE is a control document, not boilerplate to skip
- “Assume it’s allowed” is how tests become incidents
- Safety of production and people outranks engagement drama
- Changes mid-engagement require re-approval when scope expands

## Verification

- [ ] RoE is written, approved, and acknowledged by operators
- [ ] Emergency stop path is tested or clearly understood
- [ ] Scope boundaries are unambiguous to the executing team
