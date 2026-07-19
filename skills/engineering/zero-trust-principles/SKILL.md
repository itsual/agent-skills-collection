---
name: zero-trust-principles
description: >
  Apply zero-trust principles (never trust, always verify) to system design, identity, and network architecture.
  Use when designing secure systems, reviewing access patterns, or moving away from perimeter-based security.
---

# Zero Trust Principles

## Overview

Zero Trust assumes no implicit trust based on network location. Every access request should be authenticated, authorized, and continuously validated.

## When to Use

- Designing new systems or major features with security implications
- Moving from traditional perimeter/VPN models
- Reviewing service-to-service or user-to-service access

## Core Principles

- Authenticate and authorize every request
- Least privilege access
- Assume breach — limit blast radius
- Continuous validation rather than one-time checks at the perimeter
- Encrypt traffic in transit (and sensitive data at rest)
- Make access decisions based on identity, device, context, and risk signals where possible

## Practical Implications

- Strong identity for users *and* services (workload identity)
- Network segmentation / micro-segmentation
- Short-lived credentials and mutual TLS where appropriate
- Comprehensive logging and monitoring of access

## Verification

- Lateral movement is difficult even if one component is compromised
- Access policies are explicit and enforceable
- There is no broad “trusted internal network” assumption
