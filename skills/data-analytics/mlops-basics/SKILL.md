---
name: mlops-basics
description: >
  Apply MLOps basics — reproducible training, model registry, deployment patterns, monitoring, and retraining triggers — for production ML.
  Use when moving models from notebook to production or stabilizing existing deployed models.
---

# MLOps Basics

## Overview

MLOps makes ML reliable in production. It covers packaging, versioning, deployment, monitoring, and lifecycle management beyond a single training run.

## When to Use

- First production model deployments
- Stabilizing fragile notebook-to-prod paths
- Setting up monitoring and retraining
- Creating shared standards for DS and engineering

## Core Practices

- Version code, data snapshots, and model artifacts
- Use a model registry with metadata and approvals
- Automate training pipelines where repetition exists
- Deploy with rollback capability
- Monitor input drift, performance, and operational health
- Define retraining and retirement criteria

## Principles

- A model is a living system, not a file
- Reproducibility is required for debugging and audit
- Monitoring without owners is noise
- Start simple; add platform complexity when pain is real

## Verification

- [ ] Models are versioned and recoverable
- [ ] Production monitoring covers critical failure modes
- [ ] Retraining/rollback paths are defined
