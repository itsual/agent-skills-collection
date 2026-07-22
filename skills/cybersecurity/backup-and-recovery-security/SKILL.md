---
name: backup-and-recovery-security
description: >
  Design backups and recovery for security resilience — immutability, offline/offsite copies, tested restores, and ransomware resistance.
  Use when improving cyber resilience, ransomware readiness, or disaster recovery security properties.
---

# Backup and Recovery Security

## Overview

Backups are a primary control against ransomware and destructive attacks — only if they cannot be deleted by the same attacker and restores actually work.

## When to Use

- Ransomware resilience programs
- DR and backup architecture reviews
- Defining recovery time/point objectives with security constraints
- Testing restore capability

## Core Practices

- Maintain offline, offsite, or immutable backup copies
- Protect backup admin credentials with highest rigor
- Encrypt backups and control key access
- Test restores on a cadence; measure actual RTO/RPO
- Segment backup infrastructure from production domains
- Document recovery runbooks for cyber scenarios, not only hardware failure

## Principles

- Backups reachable by domain admin are not ransomware-safe
- Untested backups are assumptions
- Recovery prioritization should follow business criticality
- Integrity of backups matters as much as existence

## Verification

- [ ] Immutable or offline copies exist for critical data
- [ ] Restore tests pass within target objectives
- [ ] Backup admin paths are highly controlled
