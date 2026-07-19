---
name: authentication-patterns
description: >
  Design and implement secure authentication flows (sessions, tokens, OAuth/OIDC, passwordless, MFA).
  Use when adding login, signup, token handling, session management, or integrating identity providers.
---

# Authentication Patterns

## Overview

Authentication establishes identity. Mistakes here have high impact. Prefer proven patterns and well-maintained libraries over custom cryptography.

## When to Use

- Implementing or reviewing login / signup
- Choosing between sessions, JWTs, or opaque tokens
- Integrating OAuth 2.0 / OpenID Connect
- Adding MFA or passwordless options

## Key Considerations

- Prefer standard protocols and battle-tested libraries
- Store passwords only as strong hashes (or avoid passwords entirely)
- Protect tokens and cookies (HttpOnly, Secure, SameSite, short lifetimes where appropriate)
- Plan for logout, token revocation, and session invalidation
- Consider MFA for sensitive actions or high-risk accounts
- Be explicit about what “authenticated” means in distributed systems

## Common Pitfalls

- Rolling your own crypto or session management
- Long-lived tokens without revocation strategy
- Mixing authentication and authorization concerns
- Leaking information in error messages (e.g., “user not found” vs “invalid credentials”)

## Verification

- Auth flows are tested for common attack cases (credential stuffing resistance, token leakage, etc.)
- Secrets and tokens are handled safely
- Logout and revocation behave as expected
