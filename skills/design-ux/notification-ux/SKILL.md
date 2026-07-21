---
name: notification-ux
description: >
  Design in-product notifications, toasts, alerts, and notification centers that inform without overwhelming.
  Use when building alerting systems, activity feeds, or feedback after user actions.
---

# Notification UX

## Overview

Notifications compete for attention. The right message, channel, timing, and persistence determine whether they help or annoy.

## When to Use

- Action feedback (toasts)
- System alerts and status changes
- Notification centers / inboxes
- Email/push preference design tied to in-product alerts

## Core Practices

- Match urgency to channel and persistence (toast vs banner vs inbox)
- Write concise, actionable messages
- Allow dismissal and batching
- Avoid notification spam; support preferences
- Group related notifications when volume is high
- Define read/unread and deep-link behavior

## Principles

- Not everything deserves a notification
- User control over volume builds trust
- Transient feedback shouldn’t require action unless necessary
- Critical alerts must be impossible to miss; low-priority ones must be easy to ignore

## Verification

- [ ] Severity matches presentation
- [ ] Users can manage or mute noisy categories
- [ ] Actionable notifications link to the right place
