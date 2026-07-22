---
name: supply-chain-security-cyber
description: >
  Secure the software and hardware supply chain — dependencies, build integrity, provenance, and vendor components.
  Use when hardening CI/CD, managing open-source risk, or responding to supply-chain attack threats.
---

# Supply Chain Security (Cyber)

## Overview

Supply chain attacks compromise you through something you trust: packages, images, build systems, or vendors. Defense requires integrity controls and dependency awareness.

## When to Use

- Hardening CI/CD pipelines
- Open-source dependency risk management
- Provenance and signing requirements
- Responding to ecosystem-wide package incidents

## Core Practices

- Inventory dependencies and monitor for known vulns
- Pin versions; review sudden maintained package changes
- Protect build systems and signing keys as high-value assets
- Use artifact integrity verification (checksums, signatures) where warranted
- Limit who can publish and deploy production artifacts
- Have a playbook for ecosystem compromise events

## Principles

- Your security is bounded by your least-trusted dependency
- Build pipeline compromise can bypass many downstream controls
- SBOMs help response when maintained and used
- Speed of patching transitive deps is a competitive security trait

## Verification

- [ ] Dependencies are inventoried and monitored
- [ ] CI/CD access and secrets are tightly controlled
- [ ] Critical artifacts have integrity verification
