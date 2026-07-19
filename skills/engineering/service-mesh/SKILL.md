---
name: service-mesh
description: >
  Understand when and how to use a service mesh for traffic management, security, and observability between services.
  Use when evaluating or implementing Istio, Linkerd, Consul Connect, or similar technologies.
---

# Service Mesh

## Overview

A service mesh provides a dedicated infrastructure layer for service-to-service communication, often handling mTLS, retries, observability, and traffic shaping.

## When to Use

- Many services need consistent mTLS, retries, or traffic policies
- You want to avoid implementing these concerns in every application
- Complexity of the mesh is justified by the number of services and requirements

## Key Capabilities

- Mutual TLS and identity between workloads
- Traffic management (routing, canaries, fault injection)
- Observability (metrics, traces, logs) for service communication
- Policy enforcement

## Principles

- Don’t adopt a mesh prematurely — it adds operational complexity
- Prefer simpler solutions (libraries, gateways, platform features) when they suffice
- Treat the mesh as critical infrastructure with its own reliability needs

## Verification

- Mesh provides clear value over simpler alternatives
- Failure modes of the mesh itself are understood
- Operational ownership is clear
