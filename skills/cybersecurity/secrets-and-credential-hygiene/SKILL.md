---
name: secrets-and-credential-hygiene
description: >
  Manage secrets and credentials safely — storage, rotation, injection into runtime, and prevention of accidental exposure in code and logs.
  Use when designing secret management, responding to leaked keys, or hardening CI/CD and app configs.
---

# Secrets and Credential Hygiene

## Overview

Secrets (API keys, passwords, tokens, certs) are high-value attacker targets. Hygiene means controlled storage, minimal distribution, rotation, and rapid response to leaks.

## When to Use

- Implementing secret managers and injection patterns
- CI/CD credential design
- Responding to committed secrets or public leaks
- Service identity and machine authentication design

## Core Practices

- Store secrets in purpose-built secret managers, not repos or chat
- Inject at runtime; avoid baking into images when possible
- Scope credentials tightly; prefer short-lived credentials
- Rotate on schedule and on suspicion of compromise
- Scan repos and artifacts for accidental secrets
- Audit access to production secrets

## Principles

- A secret in git is a public secret — assume compromise
- Shared long-lived credentials are an incident waiting to happen
- Human-readable runbooks should never require pasting prod keys into tickets
- Detection of exposure must trigger automated response paths

## Verification

- [ ] Production secrets are not in source control
- [ ] Rotation and revocation paths exist
- [ ] Leak scanning is active on critical repos
