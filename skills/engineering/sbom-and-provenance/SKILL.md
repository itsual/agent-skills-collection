---
name: sbom-and-provenance
description: >
  Generate, maintain, and consume Software Bills of Materials (SBOMs) and build provenance to improve transparency and security.
  Use when implementing supply-chain transparency, compliance requirements, or vulnerability management at scale.
---

# SBOM and Provenance

## Overview

SBOMs describe what is in your software. Provenance describes how it was built. Together they enable better risk management and incident response.

## When to Use

- Meeting compliance or customer requirements for transparency
- Improving vulnerability impact analysis
- Implementing SLSA-style supply-chain levels

## Practices

- Generate SBOMs as part of the build (CycloneDX or SPDX)
- Attach or store provenance (who built it, from what source, with what tools)
- Make SBOM + provenance available to downstream consumers and security tools
- Keep generation deterministic and integrated into CI
- Use SBOMs for continuous vulnerability monitoring

## Principles

- An SBOM that is not updated or consumed has limited value
- Prefer automated generation over manual lists
- Treat provenance as a security control, not just documentation

## Verification

- SBOMs are produced for released artifacts
- Provenance is verifiable and linked to the artifact
- Security tooling can consume the SBOMs effectively
