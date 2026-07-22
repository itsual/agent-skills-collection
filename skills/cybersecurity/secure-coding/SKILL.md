---
name: secure-coding
description: >
  Write and review code with secure coding practices — input validation, output encoding, safe cryptography use, and secure error handling.
  Use when implementing features, conducting code review, or reducing common vulnerability classes in source.
---

# Secure Coding

## Overview

Secure coding prevents vulnerabilities at the point of creation. Patterns beat heroics: validate input, encode output, use proven crypto, and fail closed.

## When to Use

- Feature implementation in any language/stack
- Security-focused code review
- Remediation of injection, XSS, auth bugs
- Establishing secure coding standards

## Core Practices

- Validate and sanitize untrusted input at trust boundaries
- Use parameterized queries; never concatenate SQL/commands
- Encode output for the right context (HTML, URL, etc.)
- Use well-vetted crypto libraries; never roll your own
- Handle secrets outside source code
- Avoid leaking sensitive data in logs and errors

## Principles

- Framework protections help but do not replace understanding
- Deny by default for permissions and dangerous operations
- Security review comments should be actionable and specific
- Consistency of patterns across the codebase multiplies safety

## Verification

- [ ] Dangerous operations use safe APIs/patterns
- [ ] Secrets are not in source
- [ ] Review checklist covers high-frequency vuln classes
