
---

# `DECISIONS.md`

# Technical Decisions & AI Usage Disclosure

## Project Overview

This project analyzes operational inefficiencies in surge pricing for a regional food delivery platform.

The objective was to determine whether surge incentives were:
- improving delivery speed
- reducing queue buildup
- or reacting too late after operational congestion had already formed.

The project combines:
- exploratory data analysis
- operational analytics
- statistical testing
- short-term forecasting
- and executive storytelling.

---

# AI Usage Disclosure

AI-assisted tools were used during development for:
- debugging notebook logic
- refining presentation structure
- improving executive communication
- brainstorming operational metrics
- and accelerating repetitive formatting tasks

Primary assistance included:
- ChatGPT
- Claude.ai

All findings, analysis logic, operational recommendations, and trade-off decisions were reviewed, validated, and understood independently before submission.

Non-trivial components such as:
- surge overlap analysis
- correlation testing
- forecast methodology
- operational recommendations
- and business trade-offs

can be fully explained independently.

---

# Key Technical Decisions

## Why Rolling Mean Instead of ARIMA?

The dataset covered roughly:
- 3 months
- 7 cities
- high day-to-day variance

ARIMA requires longer historical stability to generate reliable forecasts.

A rolling mean approach was selected because it:
- remains interpretable
- avoids overfitting
- performs reliably for short operational horizons
- aligns better with weekly demand planning

The focus was operational usability rather than predictive complexity.

---

## Why Correlation Was Not Presented as Causation

The analysis found:
- positive correlation between surge and slower deliveries
- r = 0.12
- statistically significant p-value

However:
correlation alone cannot prove that surge caused slower delivery.

The findings were intentionally framed as:
- operational association
- not causal proof

A production A/B test was recommended for causal validation.

---

## Why Analyze Both Aggregate and City-Level Trends?

Aggregate analysis identified:
- overall demand patterns
- surge timing behavior
- delivery inefficiencies

City-level cohort analysis validated:
- whether trends were isolated
- or system-wide

All seven cities showed similar peak structures, which supported the idea that a standardized operational policy could work effectively.

---

## Why Define Surge Misfires Conservatively?

A surge misfire was defined as:
- surge applied outside
12–14 and 19–22 peak windows

This intentionally avoided:
- ambiguous edge periods
- borderline demand fluctuations

The goal was:
high-confidence operational signal instead of aggressive anomaly detection.

---

## Why Use Narrated Notebooks?

The notebook was structured with:
- markdown explanations before each code section
- pre-run outputs
- visual storytelling

This improves:
- reproducibility
- evaluator readability
- operational communication
- cross-functional accessibility

The project prioritizes explainability alongside technical analysis.

---

## Why Focus on Operational Recommendations?

The project was designed for:
- operations leadership
- delivery strategy teams
- incentive planning

The goal was not only identifying patterns but translating them into:
- deployable operational changes
- measurable business impact
- realistic experimentation frameworks

---

# Future Improvements

With additional time, the next priorities would be:
- weather-augmented forecasting
- real-time operational dashboards
- rider location heatmaps
- production-grade experimentation
- cuisine-level demand segmentation
- automated monitoring pipelines
