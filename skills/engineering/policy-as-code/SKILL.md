---
name: policy-as-code
description: >
  Encode organizational, security, and operational policies as code so they can be versioned, tested, and automatically enforced.
  Use when implementing automated guardrails for infrastructure, deployments, or configuration.
---

# Policy as Code

## Overview

Policy as Code turns rules that used to live in wikis or people’s heads into executable, reviewable, testable artifacts.

## When to Use

- Enforcing security or compliance rules on infrastructure or deployments
- Creating guardrails for self-service platforms
- Replacing manual review checklists with automation

## Common Tools & Approaches

- OPA / Gatekeeper / Kyverno for Kubernetes
- Sentinel, Checkov, tfsec, etc. for IaC
- Custom policies in CI for application and config rules

## Practices

- Keep policies clear, documented, and versioned
- Test policies (including allowing expected valid cases)
- Provide good error messages so developers can self-correct
- Start with audit/warn mode before hard enforcement when rolling out
- Treat policy changes with the same care as application code

## Verification

- Policies correctly allow good configurations and block bad ones
- Developers understand how to satisfy the policies
- Policy coverage matches the highest-risk rules
