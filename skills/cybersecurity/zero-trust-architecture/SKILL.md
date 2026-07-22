---
name: zero-trust-architecture
description: >
  Apply zero trust principles — never trust, always verify, least privilege, assume breach — to access design and architecture.
  Use when modernizing remote access, segmenting access to applications, or reducing implicit network trust.
---

# Zero Trust Architecture

## Overview

Zero trust replaces implicit trust based on network location with continuous verification of identity, device, and context for each access request.

## When to Use

- Replacing flat VPN access models
- Designing application-level access controls
- Reducing lateral movement risk
- Hybrid and multi-cloud access strategies

## Core Practices

- Authenticate and authorize every request with strong identity
- Factor device health and context into access decisions where feasible
- Limit lateral movement with micro-segmentation / app-level gateways
- Prefer short-lived credentials and continuous evaluation
- Log access decisions for detection and forensics
- Migrate gradually from implicit trust zones

## Principles

- Zero trust is a strategy, not a single product SKU
- Identity becomes the primary control plane
- “Inside the network” is not a sufficient trust signal
- Usability failures drive shadow workarounds

## Verification

- [ ] Sensitive apps are not reachable by network location alone
- [ ] Access policies encode least privilege
- [ ] Access logs support investigation
