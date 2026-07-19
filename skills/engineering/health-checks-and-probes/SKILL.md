---
name: health-checks-and-probes
description: >
  Design meaningful liveness, readiness, and startup probes so orchestrators and load balancers route traffic correctly.
  Use when deploying to Kubernetes or any system that relies on health endpoints.
---

# Health Checks and Probes

## Overview

Bad health checks cause either unnecessary restarts or traffic being sent to broken instances. Make them accurate and cheap.

## When to Use

- Deploying services to Kubernetes or similar platforms
- Implementing /health, /ready, /live endpoints
- Debugging flapping or slow-to-start services

## Probe Types

- **Liveness** – Is the process alive? (should it be restarted?)
- **Readiness** – Can it accept traffic right now?
- **Startup** – Has it finished initializing?

## Practices

- Keep checks fast and free of heavy dependencies when possible
- Don’t make liveness depend on downstream systems (that causes cascading restarts)
- Make readiness reflect actual ability to serve useful traffic
- Include critical but cheap self-checks
- Log transitions for easier debugging

## Verification

- Probes correctly distinguish “starting”, “ready”, “alive but not ready”, and “dead”
- False positives/negatives are rare under normal conditions
