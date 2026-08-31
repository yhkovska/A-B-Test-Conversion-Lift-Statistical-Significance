# A/B Testing Analysis (BigQuery, Python & Tableau)

## Overview

This repository contains an A/B testing analysis project focused on evaluating the performance of Control and Test groups across key e-commerce funnel events.

The analysis covers conversion rate comparison, relative conversion lift, and statistical significance to determine whether observed differences between groups are statistically meaningful.

The project combines SQL-based data extraction, statistical analysis in Python, and interactive visualization in Tableau.

---

## Project Structure

### 01 — Data Extraction & Preparation

Data is extracted from Google BigQuery and prepared for further A/B test analysis.

Key metrics include:

- Control group sample size
- Test group sample size
- Control conversion rate
- Test conversion rate
- Numerator and denominator events

Focus:

- BigQuery
- SQL
- Data filtering and aggregation
- Metric preparation

---

### 02 — A/B Test Analysis

The analysis compares Control vs Test performance across key funnel events:

- Add Payment Info
- Add Shipping Info
- Begin Checkout
- New Accounts

Calculated metrics include:

- Conversion rate
- Absolute change
- Relative conversion lift
- p-value
- z-statistic
- Statistical significance

The analysis uses a significance threshold of α = 0.05.

---

### 03 — Statistical Significance

Statistical testing is used to distinguish meaningful differences from random variation.

The analysis evaluates:

- Difference in conversion rates
- Direction and magnitude of the change
- Statistical significance of the observed effect

This allows business performance changes to be evaluated together with statistical confidence rather than relying on conversion lift alone.

---

### 04 — Tableau Dashboard

The final results are presented in an interactive Tableau dashboard.

The dashboard includes:

- Control vs Test conversion rates
- Relative conversion lift
- Statistical significance summary
- Control and Test group sample sizes
- Test selection for comparing multiple experiments

The dashboard is designed to provide a concise overview of A/B test performance and highlight statistically significant changes.

---

## Key Insights

Across the analyzed tests, the results demonstrate that conversion lift alone does not necessarily indicate a meaningful improvement.

Some tests showed positive conversion changes that were not statistically significant, while other results demonstrated statistically significant differences between Control and Test groups.

This highlights the importance of combining effect size with statistical significance when evaluating A/B test results.

---

## Skills Demonstrated

- A/B testing methodology
- Statistical significance testing
- Conversion rate analysis
- Relative conversion lift
- Hypothesis testing
- BigQuery SQL
- Python data analysis
- Data aggregation
- Analytical metric design
- Tableau dashboard development
- Business-oriented data interpretation

---

## Tools

- Google BigQuery
- SQL
- Python
- Pandas
- Tableau

---

## Project

Google Colab notebook:

https://colab.research.google.com/drive/1XhRWjvcnrimom9rQSFlwLuI_M4FMg8Px?usp=sharing
