---
name: grpc-and-protobuf
description: >
  Design and evolve gRPC services and Protocol Buffer contracts with compatibility and clarity in mind.
  Use when defining internal or external RPC APIs using gRPC/Protobuf.
---

# gRPC and Protocol Buffers

## Overview

gRPC + Protobuf provide efficient, strongly-typed RPCs. Compatibility discipline is critical because binary contracts are less forgiving than JSON.

## When to Use

- Designing internal service-to-service APIs
- High-performance or polyglot RPC needs
- Reviewing .proto files and breaking-change risks

## Key Practices

- Follow Protobuf best practices for field numbers and reserved fields
- Prefer additive, backward-compatible changes
- Use `reserved` for removed fields/numbers
- Document expected error model (status codes + details)
- Consider streaming use cases deliberately (unary vs server/client/bidi)
- Generate code and keep stubs in sync via CI

## Compatibility Rules (High Level)

- Do not reuse field numbers
- Do not change field types in incompatible ways
- Mark fields as `reserved` when removing them
- Be cautious with required fields (proto3 optional semantics)

## Verification

- Breaking changes are detected (buf breaking / similar)
- Generated code is up to date
- Error handling is consistent across services
