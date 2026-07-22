---
name: encryption-and-key-management
description: >
  Use encryption and key management correctly — algorithm choices, key lifecycle, TLS, and protection of data at rest and in transit.
  Use when designing data protection, reviewing crypto usage, or implementing KMS-backed encryption.
---

# Encryption and Key Management

## Overview

Encryption protects data confidentiality (and integrity with proper modes). Most failures are implementation and key management failures, not missing algorithms.

## When to Use

- Data-at-rest and in-transit protection design
- TLS configuration and certificate management
- KMS/HSM integration
- Reviewing application crypto usage

## Core Practices

- Use standard, modern algorithms and libraries — do not invent crypto
- Protect keys separately from encrypted data; restrict key access
- Define key rotation, revocation, and destruction policies
- Enforce TLS for sensitive transit paths with strong configuration
- Manage certificates lifecycle to avoid expiry outages and weak ciphers
- Consider integrity and authentication (e.g. AEAD) not only confidentiality

## Principles

- Encryption with exposed keys is decoration
- Home-grown crypto is a red flag
- Performance concerns rarely justify obsolete ciphers today
- Key custody and access audit matter as much as algorithm choice

## Verification

- [ ] Sensitive data classes have encryption requirements met
- [ ] Keys are managed in approved systems with access control
- [ ] TLS configurations meet modern baseline standards
