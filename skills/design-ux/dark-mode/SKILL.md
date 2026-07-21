---
name: dark-mode
description: >
  Design and implement dark mode (and theming) that maintains hierarchy, accessibility, and brand quality in low-light interfaces.
  Use when adding dark theme support, refining theme tokens, or ensuring parity between light and dark experiences.
---

# Dark Mode

## Overview

Dark mode is not an inversion of light mode. It requires deliberate elevation, contrast, and color decisions to keep interfaces readable and comfortable.

## When to Use

- Adding dark theme support to a product
- Building theme-aware design systems
- Fixing contrast or hierarchy issues in existing dark UI

## Core Practices

- Use semantic tokens that map to theme-specific values
- Desaturate and re-tune brand colors for dark surfaces
- Maintain elevation through surface steps, not only shadows
- Check contrast for text, icons, and interactive states
- Respect system preference and offer user override
- Test critical flows in both themes

## Principles

- Avoid pure #000 backgrounds in most product UIs
- Don’t rely on opacity tricks that tank contrast
- Images and illustrations may need theme-specific treatment
- Dark mode should feel intentional, not like a filter

## Verification

- [ ] Text and controls meet contrast requirements in dark theme
- [ ] Hierarchy remains clear on dark surfaces
- [ ] Theme switching is predictable and persistent
