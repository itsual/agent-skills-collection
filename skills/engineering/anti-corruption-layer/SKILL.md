---
name: anti-corruption-layer
description: >
  Protect your domain model from external systems by translating between external models and your own.
  Use when integrating with legacy systems, third-party APIs, or other bounded contexts that should not leak into your core model.
---

# Anti-Corruption Layer

## Overview

An Anti-Corruption Layer (ACL) isolates your model from external models so that external changes or poor designs do not infect your core domain.

## When to Use

- Integrating with legacy or poorly modeled external systems
- Consuming third-party APIs whose structure you do not want to adopt
- Mapping between two bounded contexts with different languages

## Practices

- Translate external concepts into your own ubiquitous language as early as possible
- Keep the translation logic in a dedicated layer/module
- Avoid leaking external IDs, enums, or structures deep into your domain
- Write tests around the translation boundary

## Principles

- Your core domain should speak your language, not the external system’s
- The ACL is a deliberate seam that makes future replacement easier

## Verification

- External model changes are mostly absorbed by the ACL
- Core domain code has minimal knowledge of external structures
