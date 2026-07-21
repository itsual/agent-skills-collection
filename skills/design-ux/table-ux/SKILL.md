---
name: table-ux
description: >
  Design data tables that support scanning, comparison, sorting, filtering, and bulk actions without overwhelming users.
  Use when building admin tables, data grids, list views, or operational tabular interfaces.
---

# Table UX

## Overview

Tables are workhorses for dense data. Good table UX balances information density with readability and makes common actions efficient.

## When to Use

- Admin and operations interfaces
- Financial, inventory, or log data views
- Any multi-attribute comparison or bulk workflow

## Core Practices

- Prioritize columns; support show/hide and reorder when needed
- Make sort and filter discoverable and persistent where helpful
- Align numbers and use consistent formatting
- Design row actions, bulk actions, and selection carefully
- Handle pagination, infinite scroll, or virtualization intentionally
- Provide empty, loading, and error states

## Principles

- Scanability first — hierarchy within cells matters
- Don’t put every attribute in the default view
- Sticky headers and key columns help orientation
- Mobile tables often need a different pattern (cards, prioritization)

## Verification

- [ ] Users can find and compare key attributes quickly
- [ ] Bulk actions are safe and understandable
- [ ] Density is appropriate for the primary job
