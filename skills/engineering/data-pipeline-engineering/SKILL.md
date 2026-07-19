---
name: data-pipeline-engineering
description: >
  Design reliable, observable, and maintainable data pipelines (batch and streaming).
  Use when building ETL/ELT, data ingestion, transformation, or analytics pipelines.
---

# Data Pipeline Engineering

## Overview

Data pipelines are production systems. They need the same attention to reliability, testing, and observability as any other critical path.

## When to Use

- Building or reviewing data ingestion and transformation pipelines
- Moving from ad-hoc scripts to production-grade data flows
- Improving reliability or cost of existing pipelines

## Key Concerns

- Idempotency and exactly-once / at-least-once semantics
- Schema evolution and data contracts
- Late / out-of-order data
- Monitoring of freshness, volume, and quality
- Backfill and replay capabilities
- Cost of storage and compute

## Principles

- Treat data pipelines as products with SLAs
- Make failures visible and recoverable
- Prefer declarative and testable transformations where possible

## Verification

- Pipeline health (freshness, success rate, data quality) is monitored
- Reprocessing or backfill is possible without major heroics
- Schema changes are handled deliberately
