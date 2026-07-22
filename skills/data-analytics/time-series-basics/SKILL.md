---
name: time-series-basics
description: >
  Analyze and forecast time series with awareness of trend, seasonality, autocorrelation, and evaluation that respects temporal order.
  Use when working with metrics over time, forecasting demand, or detecting temporal anomalies.
---

# Time Series Basics

## Overview

Time series data is ordered and dependent across time. Methods and validation must respect that structure or results will be optimistically wrong.

## When to Use

- KPI trending and anomaly detection
- Demand and capacity forecasting
- Seasonal business patterns
- Pre/post intervention time analysis (with caution)

## Core Practices

- Visualize level, trend, seasonality, and breaks
- Check stationarity concepts where required by methods
- Use time-based train/test splits — never random row splits for forecasting
- Start with simple baselines (naive, seasonal naive)
- Evaluate with appropriate error metrics (MAPE, MAE, RMSE, etc. as fit)
- Be cautious with causal claims from observational time series

## Principles

- Leakage from the future is the cardinal sin
- Complex models must beat simple baselines
- Regime changes break historical patterns
- Forecast uncertainty bands matter for decisions

## Verification

- [ ] Temporal validation is used
- [ ] Baselines are reported
- [ ] Seasonality/trend are considered
