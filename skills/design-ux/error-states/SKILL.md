---
name: error-states
description: >
  Design error states that help users understand what went wrong and how to recover, while preserving trust.
  Use when specifying form errors, system failures, permission issues, or any failure UI.
---

# Error States

## Overview

Errors are emotional moments. Good error design reduces frustration, enables recovery, and protects trust. Bad error design blames the user or leaves them stuck.

## When to Use

- Form validation and input errors
- System/network/server failures
- Permission and authorization failures
- Not-found and expired-link states
- Destructive action confirmations gone wrong

## Core Practices

- Say what happened in plain language
- Say how to fix it or what to try next
- Preserve user input whenever possible
- Use appropriate severity (inline vs page-level vs blocking modal)
- Log and monitor errors that indicate product problems
- Design for both user mistakes and system failures

## Principles

- Never blame the user
- Be specific — “Something went wrong” is not enough when you can say more
- Offer a path forward (retry, contact support, go back, edit)
- Match tone to severity

## Verification

- [ ] User knows what failed and what to do next
- [ ] Recovery paths exist for common errors
- [ ] Input isn’t needlessly wiped
