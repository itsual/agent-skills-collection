---
name: monolith-modularization
description: >
  Improve the internal structure of a monolith by introducing clear module boundaries, reducing coupling, and enabling future extraction if needed.
  Use when a monolith is becoming hard to change, or as a step toward possible service extraction.
---

# Monolith Modularization

## Overview

A well-structured modular monolith often provides many of the organizational benefits of microservices with far less operational cost.

## When to Use

- Monolith is painful to change or understand
- Teams are stepping on each other inside one codebase
- Preparing for possible future extraction of modules into services

## Practices

- Identify candidate modules aligned with business capabilities / bounded contexts
- Enforce dependency rules (no deep reach-ins across module internals)
- Define clear public APIs for each module
- Reduce shared database entanglement where possible
- Improve testability of modules in isolation
- Use packaging, code ownership, and architectural tests to protect boundaries

## Principles

- Modularization is valuable even if you never extract services
- Prefer modular monolith over premature microservices
- Boundaries should follow business seams more than technical layers

## Verification

- Module boundaries are visible and mostly respected
- Changes in one module rarely require changes in many others
- Ownership of modules is clear
