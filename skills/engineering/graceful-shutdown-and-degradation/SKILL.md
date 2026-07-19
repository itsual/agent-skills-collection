---
name: graceful-shutdown-and-degradation
description: >
  Implement graceful shutdown and controlled degradation so in-flight work is respected and users experience minimal disruption during failures or deploys.
  Use when handling SIGTERM, rolling deploys, or partial system failures.
---

# Graceful Shutdown and Degradation

## Overview

Systems should stop accepting new work cleanly, finish or checkpoint in-flight work, and degrade predictably when dependencies fail.

## When to Use

- Implementing shutdown hooks for services
- Improving behavior during deployments or scaling events
- Designing fallbacks for when dependencies are unavailable

## Key Practices

- Listen for termination signals and stop accepting new requests promptly
- Drain in-flight requests with a reasonable timeout
- Close connections and flush critical state
- Degrade functionality instead of failing completely when possible
- Make degraded mode visible (metrics, user messaging if appropriate)

## Principles

- Prefer controlled degradation over cascading failure
- Failures should be obvious to operators
- Shutdown should be safe to trigger frequently (as in rolling deploys)

## Verification

- Rolling deploys do not drop significant in-flight work
- Dependency failures produce predictable, observable degradation
