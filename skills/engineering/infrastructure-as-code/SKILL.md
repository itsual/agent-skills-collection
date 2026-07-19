---
name: infrastructure-as-code
description: >
  Manage infrastructure through versioned, reviewable code (Terraform, CloudFormation, Pulumi, etc.) with safe practices for state, modules, and changes.
  Use when provisioning or changing cloud and infrastructure resources.
---

# Infrastructure as Code

## Overview

IaC makes infrastructure changes reviewable, repeatable, and auditable. Poor IaC practices create outages and security holes just like poor application code.

## When to Use

- Provisioning or modifying cloud resources
- Standardizing environments
- Reviewing Terraform / Pulumi / CloudFormation changes

## Core Practices

- Store code in version control and review changes via PRs
- Use remote state with locking
- Prefer small, composable modules with clear interfaces
- Separate plan and apply; require human approval for production when appropriate
- Manage secrets carefully (never in plain state or code)
- Prefer immutable infrastructure patterns where practical

## Principles

- Infrastructure changes should be as deliberate as application changes
- Drift should be detectable and minimized
- Blast radius of any single change should be limited

## Verification

- Changes are planned and reviewed before apply
- State is secure and consistent
- Modules are reusable without excessive complexity
