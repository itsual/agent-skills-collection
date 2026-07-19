---
name: multi-tenancy-design
description: >
  Design systems that safely serve multiple tenants with proper isolation, configuration, and scaling characteristics.
  Use when building SaaS products or any system that hosts multiple customers in a shared environment.
---

# Multi-Tenancy Design

## Overview

Multi-tenancy improves efficiency but introduces isolation, noisy-neighbor, and data-leakage risks that must be designed for explicitly.

## When to Use

- Building SaaS or multi-customer platforms
- Deciding between pooled, siloed, or hybrid tenancy models
- Reviewing tenant isolation

## Key Decisions

- Tenancy model (database per tenant, shared DB with tenant_id, hybrid)
- Data isolation and encryption requirements
- Noisy neighbor protection (rate limits, resource quotas)
- Tenant-specific configuration and feature flags
- Onboarding, offboarding, and data deletion (including GDPR-style requirements)

## Principles

- Isolation is a security and compliance property, not just an implementation detail
- Make tenant context explicit in every relevant operation
- Design for the operational realities of many tenants

## Verification

- Cross-tenant data access is prevented and tested
- Resource isolation or quotas exist where needed
- Tenant lifecycle operations are well-defined
