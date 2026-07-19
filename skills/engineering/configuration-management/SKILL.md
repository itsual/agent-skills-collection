---
name: configuration-management
description: >
  Manage application and infrastructure configuration cleanly across environments with clear ownership and safe defaults.
  Use when dealing with environment-specific settings, feature toggles, or configuration sprawl.
---

# Configuration Management

## Overview

Configuration is code’s quieter sibling. Poor configuration practices cause environment drift, outages, and security issues.

## When to Use

- Setting up new services or environments
- Dealing with “works on my machine” / environment drift
- Managing feature flags, defaults, and overrides

## Principles

- Keep configuration separate from code
- Make configuration explicit and documented
- Prefer safe defaults
- Avoid scattering the same setting in many places
- Support progressive delivery and per-environment overrides cleanly
- Validate configuration at startup when possible

## Practices

- 12-factor style config via environment or mounted secrets/config
- Typed configuration objects
- Clear precedence rules (defaults < env < explicit overrides)
- Auditability of changes in production config

## Verification

- Configuration required for startup is validated
- Differences between environments are intentional and documented
- Sensitive config is handled via secrets management
