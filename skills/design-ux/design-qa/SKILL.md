---
name: design-qa
description: >
  Perform design quality assurance to ensure implemented UI matches design intent, system standards, and accessibility expectations.
  Use when reviewing builds against mockups, catching visual regressions, or raising implementation quality before release.
---

# Design QA

## Overview

Design QA closes the gap between approved designs and what ships. It catches spacing issues, state gaps, accessibility misses, and inconsistencies before users do.

## When to Use

- Pre-release visual and interaction review
- Verifying design system adoption in implementation
- Regression checks after large UI changes
- Partnering with engineering on polish passes

## Core Practices

- Compare implementation to source designs and specs
- Check all key states (hover, focus, disabled, error, empty, loading)
- Validate spacing, typography, and alignment against the system
- Test keyboard access and basic screen reader structure
- File issues with severity and clear reproduction steps
- Distinguish “must fix” from “nice polish”

## Principles

- QA is collaboration, not gotcha culture
- Prioritize user-facing impact over pixel-nitpicking
- Automate what you can; human-review what matters most
- Feed repeated issues back into the design system or templates

## Verification

- [ ] Critical screens match design intent in primary states
- [ ] Accessibility basics are not regressing
- [ ] Issues are tracked with clear severity
