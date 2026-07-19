# Agent Skills Collection

**A comprehensive, production-ready collection of high-quality Agent Skills** for Claude, Codex, Cursor, Gemini CLI, and other AI coding agents.

Built following the [Anthropic Agent Skills standard](https://github.com/anthropics/skills) with best practices from leading open collections (Addy Osmani, Alireza Rezvani, and others).

> **Goal**: 500+ modular, battle-tested skills organized by domain, with strong verification steps, clear triggering descriptions, and progressive disclosure.

## Current Status

**Phase 1 – Engineering & Software Development** (in progress)

We are prioritizing **Tier-1 high-frequency skills** first:

- Code review & quality
- Planning & task breakdown
- Spec-driven development
- Test-driven development
- Security & hardening
- Incremental implementation
- Debugging & error recovery
- Git workflow
- Skill creator (meta)
- Using agent skills (meta)

These form the foundation for reliable agent behavior.

## Repository Structure

```
agent-skills-collection/
├── README.md
├── LICENSE
├── skills/
│   ├── engineering/                 # Core software engineering workflows
│   │   ├── code-review-and-quality/
│   │   ├── planning-and-task-breakdown/
│   │   ├── spec-driven-development/
│   │   ├── test-driven-development/
│   │   ├── security-and-hardening/
│   │   ├── incremental-implementation/
│   │   ├── debugging-and-error-recovery/
│   │   ├── git-workflow-and-versioning/
│   │   └── ...
│   ├── meta/                        # Skill creation & discovery
│   │   ├── skill-creator/
│   │   └── using-agent-skills/
│   ├── document-production/         # Coming next (docx, pptx, xlsx, pdf)
│   └── ...
└── packs/                           # Future: curated skill packs for easy install
```

Each skill is a folder containing a `SKILL.md` (required) plus optional `scripts/`, `references/`, and `assets/`.

## Skill Format

Every skill follows this structure:

```yaml
---
name: skill-name
description: >
  Strong, slightly pushy description of *when* to use this skill.
  This is the primary triggering mechanism. Be specific about user intents,
  file types, and contexts. Prefer slightly broader triggering over under-triggering.
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
# Clone or add as marketplace (once published)
git clone https://github.com/itsual/agent-skills-collection.git
# Then copy desired skills into ~/.claude/skills/
```

### Other Agents
Most modern agents that support the Agent Skills standard (or SKILL.md) can load these directly.

## Roadmap

- [x] Repository foundation
- [ ] Core Engineering skills (first 15–20)
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
