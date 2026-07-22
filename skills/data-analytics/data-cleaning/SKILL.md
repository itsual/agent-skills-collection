---
name: data-cleaning
description: >
  Clean and prepare datasets — missing values, types, duplicates, outliers, and consistency — with documented, reversible transformations.
  Use when preparing data for analysis, modeling, or reporting pipelines.
---

# Data Cleaning

## Overview

Data cleaning turns raw extracts into analysis-ready tables. Transparent, auditable cleaning prevents silent bias and unreproducible results.

## When to Use

- Preparing analysis or model training data
- Integrating multiple sources
- Fixing recurring quality issues in pipelines
- Handing off clean tables to others

## Core Practices

- Define “clean enough” for the specific question
- Handle missing data with explicit strategy (drop, impute, flag)
- Standardize types, categories, and units
- Deduplicate with clear entity keys
- Treat outliers with investigation, not automatic deletion
- Log every transformation for reproducibility

## Principles

- Cleaning choices are analytical choices — document them
- Silent row drops are a common source of error
- Fix upstream when the same dirt reappears
- Never overwrite raw source data

## Verification

- [ ] Transformation log exists
- [ ] Row counts and key aggregates are reconciled pre/post
- [ ] Missing-data strategy is justified
