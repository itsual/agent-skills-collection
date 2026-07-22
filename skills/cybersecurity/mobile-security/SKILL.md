---
name: mobile-security
description: >
  Secure mobile apps and devices — store data carefully, protect APIs, manage devices, and reduce mobile-specific risks.
  Use when building or reviewing iOS/Android apps or mobile device management programs.
---

# Mobile Security

## Overview

Mobile security covers client apps, their backends, and the devices they run on. Local storage, insecure communications, and lost devices are common issues.

## When to Use

- Mobile application security reviews
- MDM/MAM program design
- Handling sensitive data in mobile clients
- BYOD policy and control decisions

## Core Practices

- Minimize sensitive data stored on device; encrypt what must remain
- Use platform secure storage APIs appropriately
- Enforce TLS; pin where threat model justifies
- Authenticate to APIs securely; protect tokens on device
- Manage devices with policy for corporate data access
- Test for reverse engineering and client-side trust assumptions

## Principles

- Client-side controls are bypassable — critical enforcement is server-side
- Lost/stolen devices are a baseline threat
- Sideloaded and jailbroken/rooted devices change the trust model
- SDK and third-party library risk applies on mobile too

## Verification

- [ ] Sensitive data storage choices are justified and protected
- [ ] API auth and TLS meet policy
- [ ] Device management covers corporate data access paths
