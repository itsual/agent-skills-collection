---
name: master-data-management
description: >
  Manage master data — customers, products, accounts, locations — so core entities are consistent, deduplicated, and authoritative across systems.
  Use when multiple systems disagree on “the same” customer or product, or when building golden records.
---

# Master Data Management (MDM)

## Overview

Master data is the shared core entities the business runs on. MDM creates authoritative, consistent records and keeps them synchronized across systems.

## When to Use

- Customer or product identity fragmentation
- Post-merger data consolidation
- Analytics requiring consistent entity keys
- Operational processes broken by duplicate masters

## Core Practices

- Define entity domains and golden-record rules
- Match/merge with transparent survivorship rules
- Establish source system hierarchy and write-back policy
- Govern changes to master attributes
- Monitor duplicate rates and match quality
- Integrate MDM outputs into operational and analytical systems

## Principles

- MDM is organizational agreement encoded in rules — not only software
- Over-aggressive merging destroys distinct real entities
- Stewardship is required for exceptions match engines cannot resolve
- Start with one high-pain domain, prove value, expand

## Verification

- [ ] Entity definitions and survivorship rules are documented
- [ ] Duplicate/match metrics are monitored
- [ ] Downstream systems consume the authoritative source
