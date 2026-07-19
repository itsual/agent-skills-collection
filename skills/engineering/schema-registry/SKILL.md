---
name: schema-registry
description: >
  Manage evolving data and event schemas with a schema registry to ensure compatibility and safe evolution.
  Use when multiple producers and consumers share event or data contracts that change over time.
---

# Schema Registry

## Overview

A schema registry stores and validates schemas (often Avro, Protobuf, or JSON Schema) so producers and consumers can evolve independently while maintaining compatibility.

## When to Use

- Event-driven systems with multiple producers/consumers
- Need for enforced compatibility (backward, forward, full)
- Reducing “it works on my schema” integration bugs

## Practices

- Choose a compatibility mode deliberately (backward is a common default)
- Version schemas and document changes
- Integrate schema validation into CI and runtime where appropriate
- Avoid tight coupling to a particular registry implementation in core domain logic

## Principles

- Schemas are contracts — treat changes with care
- Compatibility rules should be explicit and enforced

## Verification

- Incompatible schema changes are rejected automatically
- Consumers can handle the range of schemas they are expected to see
