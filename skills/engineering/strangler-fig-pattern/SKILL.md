---
name: strangler-fig-pattern
description: >
  Incrementally replace a legacy system by gradually routing more functionality to new implementations until the old system can be retired.
  Use when modernizing or replacing large legacy systems with reduced risk.
---

# Strangler Fig Pattern

## Overview

Named after the strangler fig tree, this pattern grows a new system around the old one and eventually replaces it, avoiding a big-bang rewrite.

## When to Use

- Replacing a legacy monolith or major subsystem
- Risk of a full rewrite is unacceptable
- You can intercept calls to the old system (facade, proxy, routing layer)

## Core Approach

1. Identify a seam or entry point where you can intercept traffic
2. Route selected functionality to the new implementation
3. Incrementally migrate more behavior
4. Keep the old system working for remaining paths
5. Eventually remove the old system when traffic is fully migrated

## Principles

- Prefer incremental value delivery over a long rewrite project
- Make the routing / facade explicit and observable
- Continuously reduce the surface area of the legacy system

## Verification

- Migration progress is measurable
- Both old and new paths are correctly routed and tested
- Legacy system can be retired with confidence when ready
