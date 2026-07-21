---
name: loading-states
description: >
  Design loading, skeleton, and progressive rendering states that manage expectations and perceived performance.
  Use when specifying waits, async operations, or data-fetching UI across a product.
---

# Loading States

## Overview

Waiting is part of software. Good loading design reduces uncertainty, improves perceived speed, and prevents layout jump when content arrives.

## When to Use

- Initial page/section loads
- Inline async actions (save, refresh, generate)
- Long-running operations
- Streaming or progressive data display

## Core Practices

- Prefer skeleton screens that match final layout for content-heavy views
- Use spinners for small, local, indeterminate waits
- Show progress when duration is known or estimable
- Avoid layout shift when content loads
- Provide cancel or background options for long tasks
- Design timeout and failure recovery

## Principles

- Perceived performance matters as much as actual performance
- Indicate that the system heard the user immediately
- Don’t block the entire UI for local operations
- Optimistic UI can help when failures are rare and reversible

## Verification

- [ ] Users know the system is working during waits
- [ ] Final content doesn’t jump jarringly into place
- [ ] Long operations have escape or status visibility
