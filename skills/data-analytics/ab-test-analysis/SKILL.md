---
name: ab-test-analysis
description: >
  Analyze A/B tests end-to-end — data quality, SRM, metrics, segments, and decision recommendations with uncertainty.
  Use when reading experiment results and advising ship/iterate/kill decisions.
---

# A/B Test Analysis

## Overview

A/B test analysis turns experimental data into a decision. It requires quality checks first, pre-specified metrics, and resistance to story-seeking in segments.

## When to Use

- Experiment readouts and decision meetings
- Diagnosing surprising or null results
- Comparing treatment effects with guardrails
- Post-hoc investigation (labeled as exploratory)

## Core Practices

- Verify assignment integrity and SRM
- Check data completeness and exposure definitions
- Analyze primary metric with planned method
- Review guardrails for harm
- Treat segment cuts as exploratory unless pre-specified
- Recommend ship / iterate / abandon with effect size + uncertainty

## Principles

- Never skip quality checks because the result “looks significant”
- Peeking and optional stopping distort inference
- Practical significance drives decisions, not p-values alone
- Null results are informative when powered adequately

## Verification

- [ ] SRM and data quality passed
- [ ] Primary metric analysis matches the design
- [ ] Decision accounts for effect size and uncertainty
