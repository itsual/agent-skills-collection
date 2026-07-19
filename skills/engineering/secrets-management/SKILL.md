---
name: secrets-management
description: >
  Handle secrets (API keys, credentials, certificates, tokens) securely throughout their lifecycle.
  Use whenever secrets are created, stored, injected, rotated, or accessed by applications.
---

# Secrets Management

## Overview

Secrets that leak become incidents. Treat them as sensitive from creation to destruction.

## When to Use

- Introducing new credentials or API keys
- Reviewing how applications receive configuration
- Implementing rotation or short-lived credentials
- Auditing for secrets in code or logs

## Core Practices

- Never commit secrets to source control
- Prefer secret managers or platform-native secret injection over environment variables when possible
- Use short-lived credentials where feasible
- Rotate secrets regularly and have a revocation plan
- Avoid logging secrets
- Scope secrets to least privilege

## Red Flags

- Secrets in source code, container images, or Terraform state without proper protection
- Long-lived static credentials with broad permissions
- Shared secrets across many services without rotation strategy

## Verification

- Secrets scanning is clean
- Runtime access follows least privilege
- Rotation and revocation paths exist
