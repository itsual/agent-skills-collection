---
name: browser-testing
description: >
  Verify UI behavior using browser automation, visual checks, and DevTools-style inspection.
  Use for end-to-end flows, visual regressions, accessibility in the browser, or when unit tests are insufficient for user-facing behavior.
---

# Browser Testing

## Overview

Some behaviors can only be confidently verified in a real browser. Use browser testing selectively for high-value user flows and visual/accessibility checks.

## When to Use

- Critical user journeys (login, checkout, core workflows)
- Visual or layout regressions
- Accessibility validation in a real browser
- Debugging frontend issues that only appear at runtime

## Core Practices

- Prefer stable selectors (roles, labels, test ids) over brittle CSS/XPath
- Keep E2E tests focused and relatively few — they are slower and more fragile
- Combine with component and unit tests for speed
- Capture screenshots or traces on failure for easier debugging
- Run against realistic data and viewports when relevant

## Verification

- Critical paths have automated browser coverage or a clear manual test script
- Failures produce actionable artifacts (screenshots, traces, logs)
