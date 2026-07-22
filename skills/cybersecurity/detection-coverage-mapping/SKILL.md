---
name: detection-coverage-mapping
description: >
  Map detection and control coverage against ATT&CK (or equivalent) techniques — honest heatmaps, gaps, and prioritization from exercises and telemetry.
  Use when measuring blue-team coverage, planning purple team roadmaps, or reporting defensive capability.
---

# Detection Coverage Mapping

## Overview

Coverage mapping shows which adversary techniques you can prevent, detect, or neither. Done honestly, it guides investment; done as theater, it invents green cells.

## When to Use

- After red/purple exercises
- Building a detection engineering roadmap
- Board/technical reporting on defensive capability
- Comparing coverage before/after control changes

## Core Practices

- Choose a framework layer (e.g. ATT&CK tactics/techniques relevant to your stack)
- Define scoring clearly: prevented / detected with alert / telemetry only / blind
- Base scores on tests and telemetry reality, not documentation claims
- Prioritize gaps on techniques used by relevant adversaries and on critical paths
- Link each gap to backlog work (telemetry, rule, control, process)
- Refresh maps on a cadence and after major stack changes

## Principles

- “We have a tool that could detect X” ≠ “we detect X in production”
- Coverage of irrelevant techniques is vanity
- Purple team results should update the map quickly
- Trend lines matter more than a single perfect heatmap slide

## Verification

- [ ] Scoring definitions are explicit and consistent
- [ ] High-priority gaps have owners and actions
- [ ] Map is updated from real exercises/telemetry, not aspiration
