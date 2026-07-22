---
name: retail-credit-risk-monitoring
description: >
  Monitor credit risk for individual and retail customers — application and behavioral scoring, bureau signals, delinquency, and portfolio early warnings.
  Use when managing consumer lending, credit cards, personal loans, retail EMI, or individual borrower risk after origination.
---

# Retail Credit Risk Monitoring

## Overview

Retail credit risk monitoring tracks whether individual borrowers remain likely to repay after the loan is booked. It combines scorecards, bureau updates, account behavior, and collections signals so risk teams can intervene before losses crystallize.

## When to Use

- Consumer loans, credit cards, overdrafts, BNPL, and retail EMI portfolios
- Post-origination behavioral scoring and account management
- Delinquency forecasting and collections prioritization for individuals
- Regulatory or internal retail portfolio risk reporting

## Core Practices

- Maintain application score (origination) and behavioral score (ongoing) views
- Refresh bureau and internal performance data on a defined cadence
- Track days-past-due (DPD) buckets, roll rates, and cure rates
- Segment accounts by risk (e.g. current, early delinquency, hard collections)
- Set limit management and line-decrease/increase rules by risk band
- Monitor product-level vintage curves and loss emergence
- Align collections treatment with risk segment and customer vulnerability policies

## Key Signals (illustrative)

- Missed payments, utilization spikes, revolving stress
- Bureau score deterioration or new adverse trades
- Income/employment disruption proxies where available
- Contactability and promise-to-pay outcomes
- Cross-product contagion within the same customer

## Principles

- Retail risk is portfolio statistics plus account-level action
- Early delinquency is cheaper to cure than late-stage recovery
- Score stability and population shift must be monitored (model risk)
- Fair treatment and regulatory conduct rules constrain collections tactics
- Vintage analysis reveals whether new originations are riskier than old ones

## Verification

- [ ] Behavioral and delinquency metrics are produced on a reliable schedule
- [ ] Risk segments drive different account actions (limits, outreach, forbearance)
- [ ] Vintage and roll-rate views explain portfolio movement
- [ ] Model/score monitoring includes stability and performance checks
