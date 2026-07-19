---
name: observability-and-instrumentation
description: >
  Add structured logging, metrics, and tracing so systems are debuggable and operable in production.
  Use when implementing new services, adding important features, or improving production readiness.
---

# Observability and Instrumentation

## Overview

If you cannot observe it, you cannot operate it. Instrument as you build, not as an afterthought.

## When to Use

- Building new services or major features
- Preparing for production
- Investigating production issues (to improve future signal)
- Defining SLOs or alerts

## Core Practices

### Logging
- Structured (JSON) preferred
- Include request/correlation IDs
- Log at appropriate levels
- Avoid logging secrets or high-cardinality sensitive data

### Metrics
- RED (Rate, Errors, Duration) for services
- USE (Utilization, Saturation, Errors) for resources
- Business metrics where they aid decisions

### Tracing
- Propagate context across service boundaries
- Focus on critical paths first

### Alerting
- Alert on symptoms (user-impacting) more than causes
- Make alerts actionable
- Avoid noisy alerts that train people to ignore them

## Checklist

- [ ] Key operations have timing and error metrics
- [ ] Logs allow tracing a request across components
- [ ] Dashboards exist for the golden signals
- [ ] Alerts are defined for true pain points

## Verification

- You can answer “is it working?” and “why is it slow/failing?” from the instrumentation
- New code paths are not invisible in production
