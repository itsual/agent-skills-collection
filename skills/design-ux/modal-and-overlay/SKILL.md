---
name: modal-and-overlay
description: >
  Design modals, drawers, popovers, and overlays that focus attention appropriately without trapping or confusing users.
  Use when specifying dialogs, confirmation flows, or layered UI patterns.
---

# Modal and Overlay

## Overview

Overlays interrupt. They should be used when focus is required — not as a default container for every secondary task.

## When to Use

- Confirmations for destructive or irreversible actions
- Focused tasks that shouldn’t lose context entirely
- Quick create/edit flows
- Teaching moments and progressive disclosure

## Core Practices

- Choose the right pattern (modal vs drawer vs popover vs inline)
- Make titles and primary actions clear
- Support keyboard focus trap and Escape to dismiss when appropriate
- Don’t stack modals deeply
- Preserve underlying context when possible
- Handle long content with internal scroll, not endless page growth

## Principles

- Prefer non-blocking patterns when interruption isn’t necessary
- One primary action per modal in most cases
- Destructive actions need clear labeling and sometimes confirmation typing
- Accessibility: focus management is mandatory

## Verification

- [ ] User understands why the overlay appeared
- [ ] Dismiss and complete paths are obvious
- [ ] Keyboard and screen reader behavior is correct
