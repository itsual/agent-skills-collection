---
name: attack-path-analysis
description: >
  Analyze and communicate attack paths — chained weaknesses from entry to impact — so leaders see business risk, not isolated CVEs.
  Use when reporting red team results, prioritizing remediation, or modeling how adversaries would traverse the environment.
---

# Attack Path Analysis

## Overview

Attack path analysis connects individual weaknesses into end-to-end narratives: how an adversary moves from initial access to a business-impacting objective. Paths drive better prioritization than severity scores alone.

## When to Use

- Red team and pen test reporting
- Prioritizing remediation across many findings
- Explaining risk to executives and boards
- Validating whether a control breaks a critical path

## Core Practices

- Start from objectives (crown jewels / critical functions)
- Map viable entry points and privilege escalation steps
- Chain identity, network, application, and human elements
- Estimate realism using likelihood of each step in context
- Identify “choke point” controls that break multiple paths
- Present timelines and decision points defenders missed or caught
- Recommend fixes that shorten or eliminate high-value paths first

## Principles

- A Critical CVE on an unreachable host may matter less than a Medium on the path to AD/cloud admin
- Identity paths are as important as software exploits
- One well-documented path beats fifty disconnected findings for decision-making
- Re-evaluate paths after major architecture or identity changes

## Verification

- [ ] Paths end in explicit business impact
- [ ] Steps are evidenced, not speculative hand-waving
- [ ] Remediation prioritizes path-breaking controls
