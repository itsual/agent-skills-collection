---
name: data-lineage
description: >
  Capture and use data lineage — where data comes from, how it transforms, and what depends on it — for impact analysis, debugging, and trust.
  Use when tracing metric origins, assessing change impact, or diagnosing broken pipelines.
---

# Data Lineage

## Overview

Lineage maps the path from source systems through transformations to reports and models. It is essential for debugging, impact analysis, and auditability.

## When to Use

- Diagnosing incorrect dashboard numbers
- Assessing downstream impact of schema or logic changes
- Audit and regulatory traceability needs
- Building trust in complex transformation graphs

## Core Practices

- Capture lineage at useful granularity (table, column, or job level as needed)
- Automate extraction from warehouses, ETL/ELT, and BI tools where possible
- Use lineage in change management (who must be notified)
- Combine technical lineage with business explanations of transforms
- Keep lineage current as pipelines evolve
- Prioritize critical metric paths first

## Principles

- Partial accurate lineage beats comprehensive stale lineage
- Column-level lineage is high value for contested metrics
- Lineage is a means to faster, safer change — not an end in itself
- Manual documentation alone does not scale

## Verification

- [ ] Critical metrics can be traced to sources
- [ ] Change impact can identify key downstream consumers
- [ ] Lineage tooling is maintained, not abandoned
