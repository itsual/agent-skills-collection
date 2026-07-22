---
name: security-architecture
description: >
  Design security architecture that embeds controls into systems — patterns for isolation, secure boundaries, and scalable guardrails.
  Use when reviewing enterprise or product security architecture or setting reference patterns for teams.
---

# Security Architecture

## Overview

Security architecture defines how controls fit together across identity, network, application, data, and operations. Good architecture makes the secure path the easy path.

## When to Use

- Enterprise or product security reference architectures
- Major platform or integration designs
- Establishing patterns for recurring problems (auth, multi-tenant isolation)
- Bridging security requirements and engineering design

## Core Practices

- Start from assets, threats, and business constraints
- Choose patterns: isolation, gateways, identity-centric access, secure SDLC gates
- Standardize approved building blocks to reduce one-off risk
- Document trust boundaries and control placement
- Plan for operability: logging, key rotation, incident needs
- Review architecture at change points, not only at inception

## Principles

- Architecture that teams cannot implement will be bypassed
- Consistency of patterns beats perfect unique designs per team
- Security architecture must account for failure modes
- Draw diagrams that show trust, not only boxes and arrows

## Verification

- [ ] Trust boundaries and controls are explicit in designs
- [ ] Standard patterns exist for common needs
- [ ] Operability of controls was considered
