# Agent Skills Collection

**A comprehensive, production-ready collection of high-quality Agent Skills** for Claude, Codex, Cursor, Gemini CLI, and other AI coding agents.

Built following the [Anthropic Agent Skills standard](https://github.com/anthropics/skills) with best practices from leading open collections.

> **Goal**: 500+ modular, battle-tested skills organized by domain, with strong verification steps, clear triggering descriptions, and progressive disclosure.

## Current Status

**Phase 1 – Engineering & Software Development** ✅ (85 skills)  
**Phase 2 – Document Production** 🚀 (in progress)  
**Skills added so far**: **94** (2 Meta + 85 Engineering + 7 Document Production)

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### 📄 Document Production

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 📝 | **docx** | Create and edit professional Word documents (.docx) with clean structure and formatting | [View](skills/document-production/docx/) |
| 📊 | **pptx** | Create clean, professional PowerPoint / presentation decks (.pptx) | [View](skills/document-production/pptx/) |
| 📈 | **xlsx** | Create well-structured, usable Excel spreadsheets (.xlsx) with clear data and formulas | [View](skills/document-production/xlsx/) |
| 📕 | **pdf** | Create, read, and manipulate PDF documents | [View](skills/document-production/pdf/) |
| 🎨 | **document-design** | Apply strong visual and structural design principles to any document type | [View](skills/document-production/document-design/) |
| 📋 | **report-generation** | Structure and produce clear, professional reports with logical flow and actionable conclusions | [View](skills/document-production/report-generation/) |
| 🗣️ | **presentation-storytelling** | Craft compelling narrative structure and messaging for presentations | [View](skills/document-production/presentation-storytelling/) |

### ⚙️ Engineering & Software Development (85 skills)

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🔍 | **code-review-and-quality** | Multi-axis code review (correctness, readability, architecture, security, performance) | [View](skills/engineering/code-review-and-quality/) |
| 📋 | **planning-and-task-breakdown** | Break complex work into small, verifiable tasks with clear acceptance criteria | [View](skills/engineering/planning-and-task-breakdown/) |
| 📝 | **spec-driven-development** | Create clear specifications and acceptance criteria before writing code | [View](skills/engineering/spec-driven-development/) |
| 🧪 | **test-driven-development** | Write failing tests first, then implement the minimum code to make them pass | [View](skills/engineering/test-driven-development/) |
| 🔒 | **security-and-hardening** | Security-focused review and hardening of code, configs, and designs | [View](skills/engineering/security-and-hardening/) |
| 🧱 | **incremental-implementation** | Implement features in thin, end-to-end vertical slices | [View](skills/engineering/incremental-implementation/) |
| 🐛 | **debugging-and-error-recovery** | Systematically reproduce, localize, fix, and guard against bugs | [View](skills/engineering/debugging-and-error-recovery/) |
| 🌿 | **git-workflow-and-versioning** | Clean Git practices: atomic commits, meaningful messages, safe history | [View](skills/engineering/git-workflow-and-versioning/) |
| 🔌 | **api-and-interface-design** | Design stable, well-documented, and evolvable APIs and interfaces | [View](skills/engineering/api-and-interface-design/) |
| ⚡ | **performance-optimization** | Measure first, then optimize the actual bottlenecks | [View](skills/engineering/performance-optimization/) |
| 📊 | **observability-and-instrumentation** | Add structured logging, metrics, and tracing for production systems | [View](skills/engineering/observability-and-instrumentation/) |
| 🎨 | **frontend-ui-engineering** | Build production-quality UIs with accessibility, performance, and maintainability | [View](skills/engineering/frontend-ui-engineering/) |
| 🧩 | **context-engineering** | Deliberately manage context loaded into the model for better reasoning | [View](skills/engineering/context-engineering/) |
| 📚 | **source-driven-development** | Verify behavior against official docs and source of truth before implementing | [View](skills/engineering/source-driven-development/) |
| ✂️ | **code-simplification** | Reduce unnecessary complexity while preserving behavior | [View](skills/engineering/code-simplification/) |
| 🚀 | **shipping-and-launch** | Prepare and execute safe releases with monitoring and rollback plans | [View](skills/engineering/shipping-and-launch/) |
| 🔄 | **ci-cd-and-automation** | Design and improve CI/CD pipelines and quality gates | [View](skills/engineering/ci-cd-and-automation/) |
| 🤔 | **doubt-driven-development** | Adversarial, fresh-context review of non-trivial decisions while building | [View](skills/engineering/doubt-driven-development/) |
| 🗑️ | **deprecation-and-migration** | Safely retire old systems and migrate users/code with minimal disruption | [View](skills/engineering/deprecation-and-migration/) |
| 📖 | **documentation-and-adrs** | Write useful docs and Architecture Decision Records that capture the *why* | [View](skills/engineering/documentation-and-adrs/) |
| 🌐 | **browser-testing** | Verify UI behavior using browser automation and DevTools-style checks | [View](skills/engineering/browser-testing/) |
| 💡 | **idea-refine** | Refine vague ideas through structured divergent and convergent thinking | [View](skills/engineering/idea-refine/) |
| 🏗️ | **architecture-review** | Evaluate system design for scalability, maintainability, and fit | [View](skills/engineering/architecture-review/) |
| 📦 | **dependency-management** | Manage dependencies safely: updates, audits, minimal footprint, lockfiles | [View](skills/engineering/dependency-management/) |
| 🚩 | **feature-flag-architecture** | Design and operate feature flags for safe rollouts and experimentation | [View](skills/engineering/feature-flag-architecture/) |
| 🚨 | **error-handling-strategy** | Design consistent, informative, and safe error handling across the stack | [View](skills/engineering/error-handling-strategy/) |
| 🔑 | **authentication-patterns** | Design and implement secure authentication flows (sessions, tokens, OAuth/OIDC, MFA) | [View](skills/engineering/authentication-patterns/) |
| 🛡️ | **authorization-patterns** | Design robust authorization (RBAC, ABAC, policies) and enforce it on every sensitive action | [View](skills/engineering/authorization-patterns/) |
| 🗄️ | **data-modeling-and-persistence** | Design clear data models, schemas, and persistence strategies | [View](skills/engineering/data-modeling-and-persistence/) |
| 💨 | **caching-strategies** | Design caching layers and invalidation strategies that improve performance safely | [View](skills/engineering/caching-strategies/) |
| 🛡️ | **resilience-patterns** | Apply retries, circuit breakers, timeouts, bulkheads, and fallbacks | [View](skills/engineering/resilience-patterns/) |
| 📡 | **event-driven-architecture** | Design event-driven systems with clear contracts and consumer patterns | [View](skills/engineering/event-driven-architecture/) |
| 🏛️ | **clean-architecture** | Structure code so business logic is independent of frameworks and external details | [View](skills/engineering/clean-architecture/) |
| 🧾 | **technical-debt-management** | Identify, track, prioritize, and systematically reduce technical debt | [View](skills/engineering/technical-debt-management/) |
| 🔢 | **api-versioning-and-compatibility** | Design APIs for safe evolution and backward compatibility | [View](skills/engineering/api-versioning-and-compatibility/) |
| 🧪 | **testing-strategy** | Define a balanced testing strategy across unit, integration, contract, and E2E tests | [View](skills/engineering/testing-strategy/) |
| 🧠 | **domain-driven-design** | Apply DDD tactical and strategic patterns to model complex business domains | [View](skills/engineering/domain-driven-design/) |
| 🧩 | **microservices-patterns** | Design, decompose, and operate microservices with appropriate patterns | [View](skills/engineering/microservices-patterns/) |
| ⏱️ | **background-jobs-and-async-processing** | Design reliable background jobs, queues, and asynchronous processing | [View](skills/engineering/background-jobs-and-async-processing/) |
| 🔁 | **idempotency-and-exactly-once** | Design operations to be safely retryable and handle duplicate execution | [View](skills/engineering/idempotency-and-exactly-once/) |
| 🚦 | **rate-limiting-and-throttling** | Protect systems and enforce fair usage with rate limiting and throttling | [View](skills/engineering/rate-limiting-and-throttling/) |
| 🏢 | **multi-tenancy-design** | Design systems that safely serve multiple tenants with proper isolation | [View](skills/engineering/multi-tenancy-design/) |
| 🔐 | **secrets-management** | Handle secrets securely throughout their lifecycle | [View](skills/engineering/secrets-management/) |
| ⚙️ | **configuration-management** | Manage configuration cleanly across environments with safe defaults | [View](skills/engineering/configuration-management/) |
| ♿ | **accessibility-engineering** | Build and verify interfaces usable by people with disabilities (WCAG-oriented) | [View](skills/engineering/accessibility-engineering/) |
| 📜 | **contract-testing** | Keep service interfaces compatible with consumer-driven or bidirectional contracts | [View](skills/engineering/contract-testing/) |
| 📈 | **load-testing-and-performance-testing** | Design and run load/stress tests that produce actionable performance results | [View](skills/engineering/load-testing-and-performance-testing/) |
| 📐 | **graphql-api-design** | Design well-structured, evolvable, and performant GraphQL APIs | [View](skills/engineering/graphql-api-design/) |
| 🔗 | **grpc-and-protobuf** | Design and evolve gRPC services and Protocol Buffer contracts | [View](skills/engineering/grpc-and-protobuf/) |
| 🔎 | **search-design-and-indexing** | Design search experiences and indexing strategies | [View](skills/engineering/search-design-and-indexing/) |
| 📁 | **file-uploads-and-storage** | Design secure, scalable file upload and storage flows | [View](skills/engineering/file-uploads-and-storage/) |
| 🔒 | **distributed-locking** | Implement safe distributed locks and coordination primitives | [View](skills/engineering/distributed-locking/) |
| 🌀 | **saga-and-distributed-transactions** | Coordinate multi-step processes across services using sagas | [View](skills/engineering/saga-and-distributed-transactions/) |
| ↔️ | **cqrs** | Apply Command Query Responsibility Segregation when read/write needs diverge | [View](skills/engineering/cqrs/) |
| 🧱 | **monolith-modularization** | Improve monolith structure with clear module boundaries | [View](skills/engineering/monolith-modularization/) |
| 🚦 | **progressive-delivery** | Release changes safely using canaries, flags, and progressive rollouts | [View](skills/engineering/progressive-delivery/) |
| 💥 | **chaos-engineering** | Deliberately inject failures to discover weaknesses and improve resilience | [View](skills/engineering/chaos-engineering/) |
| 💻 | **local-development-experience** | Improve local dev setup and feedback loops for faster productivity | [View](skills/engineering/local-development-experience/) |
| 📦 | **release-engineering** | Design reliable release processes, versioning, changelogs, and artifact promotion | [View](skills/engineering/release-engineering/) |
| 🗄️ | **database-migrations** | Design and apply safe, low-downtime database schema and data migrations | [View](skills/engineering/database-migrations/) |
| ❤️ | **health-checks-and-probes** | Design accurate liveness, readiness, and startup probes | [View](skills/engineering/health-checks-and-probes/) |
| 🛑 | **graceful-shutdown-and-degradation** | Implement graceful shutdown and controlled degradation under failure | [View](skills/engineering/graceful-shutdown-and-degradation/) |
| 📤 | **outbox-and-inbox-patterns** | Reliably publish and consume events using transactional outbox and inbox patterns | [View](skills/engineering/outbox-and-inbox-patterns/) |
| 📜 | **event-sourcing** | Persist state as a sequence of events for audit, replay, and temporal queries | [View](skills/engineering/event-sourcing/) |
| 🛡️ | **anti-corruption-layer** | Protect your domain model from external systems via translation layers | [View](skills/engineering/anti-corruption-layer/) |
| 🌱 | **strangler-fig-pattern** | Incrementally replace legacy systems by gradually routing to new implementations | [View](skills/engineering/strangler-fig-pattern/) |
| 🏗️ | **platform-engineering** | Build internal platforms and golden paths that reduce cognitive load for teams | [View](skills/engineering/platform-engineering/) |
| 📊 | **dora-and-engineering-metrics** | Use DORA and related metrics to improve delivery performance thoughtfully | [View](skills/engineering/dora-and-engineering-metrics/) |
| 📝 | **blameless-postmortems** | Run blameless post-incident reviews focused on systemic learning and action | [View](skills/engineering/blameless-postmortems/) |
| 🔗 | **supply-chain-security** | Protect the software supply chain from compromised dependencies and build systems | [View](skills/engineering/supply-chain-security/) |
| 📋 | **sbom-and-provenance** | Generate and consume SBOMs and build provenance for transparency and security | [View](skills/engineering/sbom-and-provenance/) |
| 📜 | **policy-as-code** | Encode and automatically enforce organizational and security policies | [View](skills/engineering/policy-as-code/) |
| 🏗️ | **infrastructure-as-code** | Manage infrastructure through versioned, reviewable code with safe practices | [View](skills/engineering/infrastructure-as-code/) |
| 💰 | **finops-and-cost-aware-engineering** | Design and operate systems with cost visibility and efficiency in mind | [View](skills/engineering/finops-and-cost-aware-engineering/) |
| 🌐 | **api-gateway-patterns** | Design and use API gateways for routing, policies, and backend aggregation | [View](skills/engineering/api-gateway-patterns/) |
| 📉 | **backpressure-and-flow-control** | Apply backpressure so producers do not overwhelm consumers | [View](skills/engineering/backpressure-and-flow-control/) |
| 🔄 | **data-pipeline-engineering** | Design reliable, observable, and maintainable data pipelines | [View](skills/engineering/data-pipeline-engineering/) |
| 📡 | **change-data-capture** | Capture and propagate database changes reliably using CDC | [View](skills/engineering/change-data-capture/) |
| 🔒 | **privacy-engineering** | Design systems that protect personal data through privacy-by-design practices | [View](skills/engineering/privacy-engineering/) |
| 🎯 | **threat-modeling** | Systematically identify and prioritize security threats and mitigations | [View](skills/engineering/threat-modeling/) |
| 🔐 | **zero-trust-principles** | Apply zero-trust principles (never trust, always verify) to system design | [View](skills/engineering/zero-trust-principles/) |
| 🕸️ | **service-mesh** | Use a service mesh for traffic management, security, and observability between services | [View](skills/engineering/service-mesh/) |
| 📊 | **continuous-profiling** | Use continuous profiling to understand real production resource usage | [View](skills/engineering/continuous-profiling/) |
| 📑 | **schema-registry** | Manage evolving data and event schemas with compatibility guarantees | [View](skills/engineering/schema-registry/) |
| 📝 | **data-contracts** | Define and enforce explicit data contracts between producers and consumers | [View](skills/engineering/data-contracts/) |
| 🔁 | **reproducible-builds** | Make builds deterministic for verification and supply-chain security | [View](skills/engineering/reproducible-builds/) |
| 🏛️ | **internal-developer-platform** | Design an Internal Developer Platform with self-service golden paths | [View](skills/engineering/internal-developer-platform/) |
| 📋 | **engineering-scorecards** | Use scorecards to make service and team health visible and actionable | [View](skills/engineering/engineering-scorecards/) |

---

## Repository Structure

```
agent-skills-collection/
├── README.md
├── LICENSE
├── skills/
│   ├── meta/                 # Skill creation & discovery
│   ├── engineering/          # 85 core software engineering workflows
│   ├── document-production/  # Document & presentation skills (in progress)
│   └── ...
└── packs/                    # Future: curated skill packs
```

Each skill is a folder containing a `SKILL.md` (required) plus optional `scripts/`, `references/`, and `assets/`.

## Skill Format

Every skill follows this structure:

```yaml
---
name: skill-name
description: >
  Strong, slightly pushy description of *when* to use this skill.
  This is the primary triggering mechanism.
---

# Skill Title

## Overview
...

## When to Use
...

## Core Process
...

## Verification
...
```

## How to Use

### Claude Code
```bash
git clone https://github.com/itsual/agent-skills-collection.git
# Copy desired skills into ~/.claude/skills/
```

### Other Agents
Most modern agents that support the Agent Skills / SKILL.md standard can load these directly.

## Roadmap

- [x] Repository foundation
- [x] Core Engineering skills (~85) ✅
- [x] Document Production pack (started)
- [ ] Expand Document Production (templates, advanced layout, etc.)
- [ ] Product Management pack
- [ ] Design & UX pack
- [ ] Marketing & Growth pack
- [ ] Research, Finance, Compliance, and remaining domains
- [ ] Curated “skill packs” for one-command install
- [ ] Evaluation harness and quality scoring

## Contributing

High-quality contributions are welcome. Please follow the skill authoring standard (strong description, verification steps, clear process, progressive disclosure).

## License

MIT

---

**Maintained by** [Arockia Liborious](https://github.com/itsual)
