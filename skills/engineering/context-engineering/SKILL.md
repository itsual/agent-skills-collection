---
name: context-engineering
description: >
  Deliberately manage what context is loaded, retained, and passed to the model for better reasoning and lower noise.
  Use when working on large codebases, long sessions, or when the agent seems to be missing important information or getting distracted by irrelevant details.
---

# Context Engineering

## Overview

The quality of an agent’s output is heavily influenced by the quality and relevance of the context it receives. Treat context as a scarce, high-value resource.

## When to Use

- Large or unfamiliar codebases
- Long-running tasks that accumulate history
- When the agent is making incorrect assumptions due to missing information
- When context windows are under pressure

## Core Practices

- Load only what is needed for the current step
- Prefer official docs, type definitions, and high-signal files over dumping entire directories
- Summarize or discard low-value history when possible
- Explicitly state key constraints and decisions so they persist
- Use progressive disclosure (high-level first, details on demand)

## Techniques

- Start with architecture / entry points, then drill down
- Keep a running “key facts” list for the session
- When stuck, re-state the goal and the most relevant constraints
- Avoid loading large generated files, lockfiles, or binary content unless necessary

## Verification

- The agent has the information required to make correct decisions
- Irrelevant or outdated context is not dominating reasoning
