---
name: skill-creator
description: >
  Create, improve, and evaluate new Agent Skills. Use when the user wants to build a new skill from scratch, refine an existing skill, write better descriptions for triggering, add evaluation cases, or package a skill.
  This is the meta-skill for extending the skills system itself.
---

# Skill Creator

## Overview

A systematic process for creating high-quality Agent Skills that are reliable, well-triggered, and maintainable.

## When to Use

- User asks to create a new skill
- Improving an existing skill’s description, process, or verification
- Adding tests/evals for a skill
- Packaging a skill for distribution

## Core Process

### 1. Capture Intent
- What should the skill enable the agent to do?
- When should it trigger? (phrases, file types, contexts)
- What does good output look like?
- Are there existing similar skills to learn from or avoid duplicating?

### 2. Write a Strong Description
The `description` field is the primary trigger. Make it slightly pushy and specific:
- Include concrete user intents and keywords
- Mention related file types or domains
- Prefer broader correct triggering over missing useful cases

### 3. Structure the SKILL.md
Follow the standard template:
- YAML frontmatter (name + description required)
- Overview
- When to Use (include negative cases)
- Core Process / Workflow
- Detailed guidance, checklists, gotchas
- Verification / Definition of Done
- Common pitfalls
- See Also

Keep the main body focused. Move long reference material into `references/`.

### 4. Add Verification
Every good skill has clear ways to know the work is correct (checklists, tests, visual QA, etc.).

### 5. Test the Skill
Create 2–4 realistic test prompts. Run the skill against them and iterate based on results.

### 6. Iterate on Triggering
If the skill under-triggers or over-triggers, refine the description.

## Principles

- Prefer imperative instructions and explain *why*
- Progressive disclosure (metadata → body → references)
- Strong verification prevents silent failures
- Avoid overly rigid “ALWAYS/NEVER” without reasoning
- Bundle deterministic scripts when the same mechanical work repeats

## Output

A complete skill folder ready for use:
```
skill-name/
├── SKILL.md
├── scripts/     (optional)
├── references/  (optional)
└── assets/      (optional)
```
