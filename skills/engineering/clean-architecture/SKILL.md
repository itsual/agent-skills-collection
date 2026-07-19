---
name: clean-architecture
description: >
  Structure code so that business logic is independent of frameworks, UI, and external details.
  Use when organizing larger codebases, defining layer boundaries, or fighting framework lock-in.
---

# Clean Architecture

## Overview

Keep the core domain and use cases at the center. Frameworks, databases, and UI are details that depend inward, not the other way around.

## When to Use

- Growing applications that need clearer boundaries
- Reducing coupling to frameworks or infrastructure
- Improving testability of business logic

## Core Ideas

- Dependency rule: source code dependencies point inward
- Entities and use cases should not depend on UI, database, or external services
- Interfaces (ports) define what the core needs; adapters implement them
- Test business rules without spinning up frameworks or databases

## Practical Guidance

- Start simple; don’t over-layer small applications
- Enforce boundaries with package/module structure and code review
- Be pragmatic — pure forms of the architecture are less important than clear separation of concerns

## Verification

- Core business logic can be tested in isolation
- Framework and infrastructure changes do not force widespread domain changes
