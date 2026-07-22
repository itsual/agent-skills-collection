---
name: nlp-basics
description: >
  Apply foundational NLP for analytics — text cleaning, representation, classification, and topic patterns — with awareness of limits of language models.
  Use when analyzing text data such as reviews, tickets, surveys, or documents.
---

# NLP Basics (for Analytics)

## Overview

NLP turns text into analyzable signal. For analytics work, practical pipelines and validation matter more than the newest model name.

## When to Use

- Support ticket and review analysis
- Survey open-ends theme extraction
- Document classification and routing
- Lightweight information extraction

## Core Practices

- Define the text task clearly (classify, extract, cluster, summarize)
- Clean and normalize with care for domain language
- Start with strong baselines before heavy models
- Evaluate with labeled samples and error analysis
- Watch for leakage and train/test contamination in text features
- Consider privacy when text contains personal data

## Principles

- Domain jargon breaks generic tools
- Multilingual data needs explicit strategy
- LLM outputs need evaluation like any model
- Human-in-the-loop often required for high-stakes text decisions

## Verification

- [ ] Task and success metrics are defined
- [ ] Evaluation uses realistic labeled examples
- [ ] Privacy constraints are respected
