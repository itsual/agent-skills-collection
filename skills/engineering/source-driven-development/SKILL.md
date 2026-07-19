---
name: source-driven-development
description: >
  Verify behavior and APIs against official documentation and source of truth before implementing or advising.
  Use when working with libraries, frameworks, cloud services, or any external system where assumptions are dangerous.
---

# Source-Driven Development

## Overview

LLMs can hallucinate APIs and best practices. When accuracy matters, go to the source.

## When to Use

- Using a library or framework feature you are not 100% certain about
- Cloud provider APIs, SDKs, or configuration
- Security-sensitive or version-sensitive behavior
- When previous assumptions have proven wrong

## Process

1. Identify the authoritative source (official docs, source code, RFCs, etc.)
2. Check the version that is actually in use
3. Confirm the exact API, options, and behavior
4. Only then implement or recommend

## Principles

- Prefer primary sources over blog posts or Stack Overflow
- Note version differences explicitly
- When docs are ambiguous, say so

## Verification

- Claims about external systems are backed by checked sources
- Version compatibility is considered
