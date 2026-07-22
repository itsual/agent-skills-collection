---
name: identity-and-access-management
description: >
  Design IAM controls — authentication, authorization, lifecycle, and privileged access — to enforce least privilege and reduce account takeover risk.
  Use when implementing SSO/MFA, role design, joiner-mover-leaver processes, or privileged access management.
---

# Identity and Access Management

## Overview

IAM ensures the right identities get the right access for the right reasons — and lose it when those reasons end. Most breaches involve identity abuse.

## When to Use

- SSO, MFA, and identity provider design
- Role and permission model design
- Joiner/mover/leaver access processes
- Privileged access and break-glass controls

## Core Practices

- Enforce strong authentication (MFA) for users and admins
- Prefer centralized identity with SSO where feasible
- Design roles around job functions; avoid permission sprawl
- Automate provisioning and timely deprovisioning
- Monitor and tightly control privileged accounts
- Review access periodically for high-risk systems

## Principles

- Shared accounts destroy accountability
- Standing admin rights are a liability — prefer just-in-time where practical
- Orphaned accounts are an open door
- Authorization bugs are application security issues too

## Verification

- [ ] MFA covers privileged and remote access paths
- [ ] Deprovisioning is timely and tested
- [ ] Privileged access is monitored and minimized
