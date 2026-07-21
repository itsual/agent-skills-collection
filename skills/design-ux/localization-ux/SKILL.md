---
name: localization-ux
description: >
  Design interfaces that adapt cleanly to different languages, locales, and cultural conventions without breaking layout or meaning.
  Use when preparing products for international markets or fixing layout issues caused by translation.
---

# Localization UX

## Overview

Localization is more than translation. Text expansion, RTL scripts, date/number formats, and cultural imagery all affect whether an interface still works.

## When to Use

- Expanding to new languages or regions
- Designing UI that must support i18n from the start
- Fixing truncated or broken translated layouts
- Handling RTL (right-to-left) languages

## Core Practices

- Allow for text expansion (often 30%+ from English)
- Avoid embedding text in images
- Support RTL layout mirroring where appropriate
- Use locale-aware formats for dates, times, numbers, currencies
- Design flexible containers; prefer logical properties
- Plan for pseudo-localization testing early

## Principles

- Design for the longest likely string, not the English ideal
- Cultural neutrality beats assumptions when unsure
- Icons and metaphors aren’t universal
- Truncation with tooltips is a last resort, not a strategy

## Verification

- [ ] Layouts hold up with longer strings and RTL
- [ ] Dates, numbers, and currencies format correctly per locale
- [ ] No critical text is trapped in images
