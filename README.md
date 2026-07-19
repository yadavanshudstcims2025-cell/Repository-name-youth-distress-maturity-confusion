# Repository-name-youth-distress-maturity-confusion
“Statistical and machine learning analysis of maturity, confusion, and psychological distress among youth aged 20–29, using Python.”
# Youth Distress Analytics: Maturity, Confusion, and Gender

This repository contains my MSc Statistics portfolio project analysing how psychological maturity and confusion relate to distress among youth aged 20–29 using Python and survey data.

## Files

- `notebooks/` – Jupyter notebooks with data cleaning, score construction, EDA, regression, hypothesis tests, and clustering.
- `reports/Youth_Distress_Analytics_Report.pdf` – Full written report (academically formatted) with introduction, methods, results, and discussion.

## Project Summary

- Data: Kaggle “Young People Survey” (subset of respondents aged 20–29).
- Indices:
  - `Maturity_score` – composite of responsibility, planning, reliability, punctuality, achievements, assertiveness items.
  - `Confusion_score` – composite of decision difficulty, mood swings, new environment, life struggles items.
  - `Distress_score` – composite of loss of interest, loneliness, life struggles, happiness, energy, health items (coded so higher = more distress).

- Methods:
  - Exploratory data analysis (distributions, correlations).
  - Simple and multiple OLS regression.
  - t‑tests (gender differences) and one‑way ANOVA (internet usage).
  - K‑means clustering to identify psychological profiles.

- Key findings:
  - Confusion is a strong positive predictor of distress, explaining ~20% of its variance.
  - Maturity has a weak independent effect once confusion and gender are controlled.
  - Female respondents report significantly higher distress than males.
  - Clustering reveals a high‑maturity, high‑confusion, high‑distress group, suggesting that maturity and distress can coexist when confusion is high.

