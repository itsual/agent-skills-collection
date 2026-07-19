---
name: chaos-engineering
description: >
  Deliberately inject failures to discover weaknesses and improve system resilience in a controlled way.
  Use when validating resilience mechanisms or building confidence in production reliability.
---

# Chaos Engineering

## Overview

Chaos engineering is the disciplined practice of experimenting on a system to build confidence in its ability to withstand turbulent conditions.

## When to Use

- After basic monitoring and resilience patterns are in place
- Before or after major architectural changes
- To validate timeouts, retries, fallbacks, and redundancy

## Process

1. Define steady-state behavior (what “healthy” looks like)
2. Hypothesize how the system will respond to a failure
3. Inject a realistic failure in a controlled way
4. Observe and compare to the hypothesis
5. Improve the system and the controls based on findings

## Principles

- Start small and in non-production or limited blast-radius environments
- Automate experiments where possible
- Always have abort conditions and clear ownership
- Focus on learning, not on causing outages

## Verification

- Resilience mechanisms behave as expected under failure
- Gaps discovered are turned into concrete improvements
- Experiments are repeatable and safe
