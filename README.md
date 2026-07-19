# Agent Skills Collection

**A comprehensive, production-ready collection of high-quality Agent Skills** for Claude, Codex, Cursor, Gemini CLI, and other AI coding agents.

Built following the [Anthropic Agent Skills standard](https://github.com/anthropics/skills) with best practices from leading open collections.

> **Goal**: 500+ modular, battle-tested skills organized by domain, with strong verification steps, clear triggering descriptions, and progressive disclosure.

## Current Status

**Phase 1 – Engineering & Software Development** (in progress)  
**Skills added so far**: **35** (2 Meta + 33 Engineering)

We prioritize **Tier-1 high-frequency skills** first (code review, planning, specs, TDD, security, etc.). These form the foundation for reliable agent behavior.

---

## Skills Catalog

### 🧠 Meta

| Icon | Skill | Description | Link |
|------|-------|-------------|------|
| 🛠️ | **skill-creator** | Create, improve, and evaluate new Agent Skills | [View](skills/meta/skill-creator/) |
| 🧭 | **using-agent-skills** | Discover and apply the right skills for the current task | [View](skills/meta/using-agent-skills/) |

### ⚙️ Engineering & Software Development

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

> More Engineering skills are being added continuously. Document Production, Product, Design, Marketing, and other domains are next.

---

## Repository Structure

```
agent-skills-collection/
├── README.md
├── LICENSE
├── skills/
│   ├── engineering/          # Core software engineering workflows
│   ├── meta/                 # Skill creation & discovery
│   ├── document-production/  # Coming soon (docx, pptx, xlsx, pdf)
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
- [x] Core Engineering skills (multiple batches)
- [ ] Full Engineering set (~85)
- [ ] Document Production pack (docx, pptx, xlsx, pdf)
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
