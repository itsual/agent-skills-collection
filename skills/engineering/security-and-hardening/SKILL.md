---
name: security-and-hardening
description: >
  Perform security-focused review and hardening of code, configurations, and designs.
  Use when reviewing authentication, authorization, input handling, secrets, dependencies, or any security-sensitive change.
  Also trigger on requests involving OWASP, threat modeling, secure coding, or vulnerability concerns.
---

# Security and Hardening

## Overview

Security is not a separate phase — it must be considered continuously. This skill provides a practical checklist and mindset for identifying and mitigating common risks.

## When to Use

- Reviewing authentication or authorization code
- Handling user input, file uploads, or external data
- Managing secrets, tokens, or credentials
- Adding or updating dependencies
- Designing new endpoints or data flows
- Any time the user mentions security, hardening, or vulnerabilities

## Core Checklist

### Input & Data
- [ ] All external input validated and sanitized at trust boundaries
- [ ] Output encoding applied to prevent XSS
- [ ] Parameterized queries / safe ORM usage (no string-concatenated SQL)
- [ ] File uploads restricted by type, size, and stored safely

### Authentication & Sessions
- [ ] Strong password handling (or passwordless)
- [ ] Secure session management
- [ ] Proper logout and session invalidation
- [ ] Multi-factor considerations where appropriate

### Authorization
- [ ] Checks performed on every sensitive action (not just UI hiding)
- [ ] Principle of least privilege
- [ ] IDOR / object-level authorization tested

### Secrets & Configuration
- [ ] No secrets in source code, logs, or client-side code
- [ ] Secrets loaded from environment or secret manager
- [ ] Sensitive data minimized in logs

### Dependencies & Supply Chain
- [ ] Dependencies reviewed for known vulnerabilities
- [ ] Lockfiles committed and reviewed
- [ ] Minimal dependency footprint preferred

### Other High-Impact Areas
- [ ] CSRF protection on state-changing requests
- [ ] Rate limiting on authentication and sensitive endpoints
- [ ] Security headers considered
- [ ] Error messages do not leak sensitive information

## Threat Modeling Lite

For significant features, quickly consider:
- What are the assets?
- Who are the attackers (external, internal, malicious user)?
- What can go wrong?
- What controls mitigate the highest risks?

## Verification

- Security-sensitive paths have explicit tests or review notes
- No high-severity issues left unaddressed
- Secrets scanning clean
- Dependency audit clean (or risks accepted with justification)
