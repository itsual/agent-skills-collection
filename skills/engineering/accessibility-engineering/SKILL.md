---
name: accessibility-engineering
description: >
  Build and verify interfaces that are usable by people with disabilities (WCAG-oriented accessibility engineering).
  Use for any user-facing UI work, design system components, or accessibility audits.
---

# Accessibility Engineering

## Overview

Accessibility is part of quality and, in many contexts, a legal requirement. It should be designed and tested, not bolted on.

## When to Use

- Building or reviewing UI components and pages
- Creating or updating a design system
- Responding to accessibility issues or audits

## Core Practices

- Prefer semantic HTML
- Ensure keyboard operability
- Provide adequate color contrast
- Label interactive elements properly
- Support screen readers with correct roles, names, and states
- Test with keyboard and, ideally, assistive technology
- Include accessibility in definition of done and code review

## Verification

- Critical flows are operable via keyboard only
- Automated checks (axe, Lighthouse, etc.) are clean or justified
- Manual spot-checks with screen reader for important interactions
