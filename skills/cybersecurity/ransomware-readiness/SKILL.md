---
name: ransomware-readiness
description: >
  Prepare for ransomware — prevention hardening, detection, immutable backups, recovery playbooks, and decision-making under pressure.
  Use when improving ransomware resilience or running ransomware-specific readiness programs.
---

# Ransomware Readiness

## Overview

Ransomware readiness combines prevention, rapid detection, and recovery that works when identity and production systems are partially compromised.

## When to Use

- Ransomware resilience programs
- Board-level cyber readiness discussions
- Backup and recovery design for destructive malware
- Tabletop scenarios focused on ransomware

## Core Practices

- Reduce exposure: patching, MFA, remote access hardening, email controls
- Segment networks to limit lateral movement
- Maintain immutable/offline backups tested for restore
- Detect early (EDR, unusual encryption behavior, mass file changes)
- Pre-decide communication, legal, and law-enforcement engagement paths
- Practice recovery prioritization of critical business services

## Principles

- Paying ransom is a business/legal decision with no guarantee of recovery
- Identity compromise often precedes ransomware deployment
- Untested backups fail when you need them most
- Speed of isolation beats perfect attribution in the first hours

## Verification

- [ ] Immutable or offline backups exist and restore tests pass
- [ ] Privileged access and remote entry points are hardened
- [ ] Ransomware playbook is exercised
