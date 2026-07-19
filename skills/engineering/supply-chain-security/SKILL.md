---
name: supply-chain-security
description: >
  Protect the software supply chain from compromised dependencies, build systems, and distribution channels.
  Use when reviewing dependencies, build pipelines, artifact signing, or responding to supply-chain threats.
---

# Supply Chain Security

## Overview

Modern applications are mostly assembled from third-party code. Securing the path from source to running software is essential.

## When to Use

- Adding or updating dependencies
- Hardening CI/CD and build systems
- Implementing signing, verification, or provenance
- Responding to dependency or build-system incidents

## Key Practices

- Pin and verify dependencies (lockfiles, checksums, signature verification)
- Minimize the number and privilege of build tools and runners
- Produce and verify SBOMs and provenance (e.g. SLSA-inspired)
- Sign artifacts and verify signatures before deployment
- Control who can modify build and release configuration
- Monitor for known compromised packages and unusual behavior

## Principles

- Trust but verify — assume components can be compromised
- Prefer reproducible builds where practical
- Least privilege throughout the pipeline

## Verification

- Artifacts can be traced to source and build inputs
- Critical dependencies are reviewed and pinned
- Build system changes are controlled and auditable
