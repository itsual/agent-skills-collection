---
name: reproducible-builds
description: >
  Make builds deterministic so the same source inputs always produce bit-for-bit identical artifacts when desired.
  Use when strengthening supply-chain security, enabling verification, or debugging “works on my machine” build differences.
---

# Reproducible Builds

## Overview

Reproducible builds allow anyone to verify that a binary corresponds exactly to given source code by rebuilding it independently and comparing results.

## When to Use

- High-security or regulated environments
- Implementing strong supply-chain guarantees
- Eliminating heisenbugs caused by non-deterministic builds

## Practices

- Eliminate or control sources of non-determinism (timestamps, file order, environment differences, randomness)
- Pin toolchains and dependencies
- Record build environment and inputs
- Provide tooling to rebuild and compare artifacts

## Principles

- Reproducibility is a spectrum — aim for the level justified by risk
- Determinism helps both security and debuggability

## Verification

- Independent rebuilds produce identical artifacts (or documented acceptable differences)
- Build inputs and toolchain are fully captured
