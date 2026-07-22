---
name: notebook-best-practices
description: >
  Keep analytical notebooks reproducible, readable, and handoff-ready — structure, environments, secrets, and narrative.
  Use when doing analysis in Jupyter/Colab/etc. or reviewing notebook-based work.
---

# Notebook Best Practices

## Overview

Notebooks are powerful and easy to make unreproducible. Discipline around structure, environments, and narrative turns them into assets instead of liabilities.

## When to Use

- Exploratory and presentation-ready analysis
- Sharing work with teammates
- Transitioning notebook prototypes toward pipelines
- Code review of notebook analyses

## Core Practices

- Structure: setup → data → analysis → conclusions
- Pin dependencies and document environment
- Keep secrets out of notebooks; use env/config
- Write narrative cells that explain decisions
- Restart-and-run-all before sharing
- Extract reusable logic into modules when logic stabilizes

## Principles

- Out-of-order execution is a reproducibility trap
- A notebook without conclusions is incomplete analysis
- Giant notebooks should be split by purpose
- Production paths eventually leave pure notebooks behind

## Verification

- [ ] Notebook runs top-to-bottom cleanly
- [ ] Environment is documented
- [ ] Conclusions and next steps are stated
