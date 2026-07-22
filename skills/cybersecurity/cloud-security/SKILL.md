---
name: cloud-security
description: >
  Secure cloud environments — identity, network, data, and configuration posture — under shared responsibility models.
  Use when hardening AWS/Azure/GCP (or similar) accounts, reviewing cloud architecture, or reducing misconfiguration risk.
---

# Cloud Security

## Overview

Cloud security applies least privilege, strong identity, secure defaults, and continuous posture management to elastic infrastructure. Misconfiguration is a leading cause of cloud breaches.

## When to Use

- Cloud landing zone and account design
- IAM and network hardening in cloud
- CSPM / posture review findings
- Data protection in object storage and databases

## Core Practices

- Understand shared responsibility for each service used
- Centralize identity; avoid long-lived root/admin keys
- Restrict public exposure; inventory internet-facing resources
- Encrypt data at rest and in transit with managed keys where appropriate
- Use posture management and policy-as-code for guardrails
- Log cloud control-plane and data-plane security events

## Principles

- Default-open storage buckets are a classic failure mode
- Cloud speed multiplies both good and bad patterns
- Multi-account/org structure is a security control
- “Someone else hosts it” does not mean “someone else secures your data”

## Verification

- [ ] Public exposure is known and justified
- [ ] Privileged cloud identities are tightly controlled
- [ ] Posture findings have owners and SLAs
