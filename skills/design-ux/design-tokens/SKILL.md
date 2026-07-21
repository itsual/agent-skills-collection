---
name: design-tokens
description: >
  Define and manage design tokens (color, typography, space, elevation, etc.) as the single source of truth between design and engineering.
  Use when building design systems, theming products, or improving design-dev consistency at scale.
---

# Design Tokens

## Overview

Design tokens are named, reusable design decisions. They decouple visual values from components and enable theming, consistency, and multi-platform implementation.

## When to Use

- Creating or refactoring a design system foundation
- Supporting light/dark modes or multi-brand themes
- Aligning Figma (or other tools) with code variables
- Scaling design decisions across platforms

## Core Practices

- Define token tiers (primitive → semantic → component)
- Name tokens by purpose, not raw value (e.g., `color.text.primary`)
- Document usage and forbidden combinations
- Sync tokens between design tools and code
- Version and communicate breaking token changes

## Principles

- Prefer semantic tokens for product UI; keep primitives as the raw palette
- Make tokens the only way to apply core visual decisions
- Design for change — themes and rebrands should not require component rewrites
- Keep the set manageable; token sprawl is real

## Verification

- [ ] Design and code reference the same token names and values
- [ ] Semantic tokens express intent clearly
- [ ] Theming works without one-off overrides everywhere
