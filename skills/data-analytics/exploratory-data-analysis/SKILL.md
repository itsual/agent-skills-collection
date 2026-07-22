---
name: exploratory-data-analysis
description: >
  Perform exploratory data analysis (EDA) to understand distributions, relationships, data quality issues, and promising signals before formal modeling.
  Use when first encountering a dataset or validating assumptions prior to deeper analysis.
---

# Exploratory Data Analysis

## Overview

EDA builds familiarity with the data’s shape, quality, and structure. It surfaces problems and hypotheses that formal analysis should respect.

## When to Use

- First pass on a new dataset
- Before modeling or experimentation analysis
- Investigating anomalies or unexpected results
- Documenting data characteristics for collaborators

## Core Practices

- Profile rows, columns, types, and missingness
- Examine univariate distributions and outliers
- Explore bivariate relationships relevant to the question
- Check time trends and segment differences
- Note data generation process and possible biases
- Record findings and open questions, not only plots

## Principles

- EDA is purposeful exploration, not endless charting
- Outliers may be errors or the most important cases — investigate
- Always ask how the data was produced
- Reproducible EDA notebooks beat ad-hoc GUI clicks for team work

## Verification

- [ ] Missingness and key distributions are characterized
- [ ] Data quality issues are logged
- [ ] Hypotheses for next steps are explicit
