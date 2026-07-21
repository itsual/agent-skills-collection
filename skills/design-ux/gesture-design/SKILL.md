---
name: gesture-design
description: >
  Design touch and pointer gestures that feel natural, discoverable, and forgiving — with accessible alternatives.
  Use when defining swipe, drag, pinch, long-press, or custom gesture interactions on mobile or canvas interfaces.
---

# Gesture Design

## Overview

Gestures can make interactions fluid, but hidden gestures harm discoverability. Good gesture design pairs natural motion with clear affordances and non-gesture alternatives.

## When to Use

- Mobile navigation and list actions
- Canvas, map, and media interactions
- Drag-and-drop interfaces
- Custom product-specific gestures

## Core Practices

- Prefer platform-standard gestures where they exist
- Provide visible affordances or tutorials for non-standard gestures
- Always offer an alternative to gesture-only actions
- Define hit areas, thresholds, and cancellation behavior
- Prevent conflicts with system gestures
- Test with real devices and varied hand sizes

## Principles

- Discoverability is part of usability
- Gestures should feel reversible when possible
- Don’t overload a single element with many hidden gestures
- Accessibility: keyboard and button alternatives required for critical actions

## Verification

- [ ] Critical actions are not gesture-only
- [ ] Gestures don’t conflict with system navigation
- [ ] Feedback during the gesture confirms progress
