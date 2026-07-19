---
name: frontend-ui-engineering
description: >
  Build production-quality user interfaces with attention to accessibility, performance, responsiveness, and maintainability.
  Use for any UI work, component development, frontend features, or when the user mentions React, Vue, CSS, design systems, or user-facing interfaces.
---

# Frontend UI Engineering

## Overview

Frontend code is user-facing. Quality here directly affects perception of the entire product.

## When to Use

- Building or modifying UI components and pages
- Implementing design system elements
- Addressing accessibility, responsiveness, or frontend performance

## Core Principles

- Accessibility is not optional (semantic HTML, keyboard, ARIA, contrast)
- Mobile-first / responsive by default
- Prefer composition and clear component boundaries
- Avoid unnecessary re-renders and large bundles
- Match the existing design system when one exists

## Process

1. Understand the user goal and interaction
2. Check existing components / design system before creating new ones
3. Implement with semantic structure and accessibility in mind
4. Handle loading, empty, and error states
5. Verify keyboard navigation and basic screen reader behavior
6. Check responsiveness at key breakpoints

## Checklist

- [ ] Semantic HTML elements used appropriately
- [ ] Interactive elements are keyboard accessible
- [ ] Color contrast meets WCAG AA at minimum
- [ ] Loading / empty / error states exist
- [ ] No obvious layout shift or overflow issues
- [ ] Component API is clear and documented if shared

## Verification

- Visual and interaction review in the browser
- Basic accessibility checks pass
- No major performance red flags (large unnecessary JS, layout thrashing)
