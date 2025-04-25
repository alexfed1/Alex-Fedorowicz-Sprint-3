# RN Burnout Analysis — Exploring the Causes Behind the U.S. Nursing Shortage

## Overview

This project investigates the relationship between burnout among registered nurses (RNs) and factors such as age, weekly work hours, years of nursing experience, and employment setting. The analysis uses data from the 2022 National Sample Survey of Registered Nurses (NSSRN), a nationally representative dataset compiled by the U.S. Health Resources and Services Administration (HRSA).

The goal is to identify statistically significant predictors of burnout using weighted descriptive statistics, chi-square tests, Kruskal-Wallis tests, and logistic regression, and to explore what factors contribute to RNs burout and subsequently lead to the RN shortage in the United States.

---

## Motivation

The U.S. healthcare system is facing a critical shortage of RNs, driven in part by high rates of burnout. With increasing care demands and an aging population, it is essential to better understand what drives burnout among nurses so that effective retention strategies can be developed.

---

## Methods

- **Data Source**: 2022 National Sample Survey of Registered Nurses (NSSRN)
- **Preprocessing**: Converted SAS files to CSV for analysis, removed missing values and skip pattern values
- **Key Variables**: Burnout frequency, age, education level, weekly hours worked, years in nursing, employment setting
- **Statistical Techniques**:
  - Descriptive statistics & visualizations (histograms, bar charts, heatmaps)
  - Kruskal-Wallis test (non-parametric comparison)
  - Chi-square test (association between age and burnout frequency)
  - Logistic regression (binary classification: burnout vs. no burnout)

---

## Key Findings

- **Younger nurses** had significantly higher odds of experiencing burnout (RNs <29 years: 8.3x more likely vs. RNs ≥75).
- **Longer work hours** were strongly associated with higher burnout risk.
- **Years of experience** was a protective factor (each year reduced burnout odds by 8%).
- **Employment setting** mattered: RNs in non-patient or outpatient care roles had significantly lower burnout than RNs orking in hospitals
- **Education level** was not a significant predictor of burnout in this model.

---

## Implications

Findings suggest that burnout prevention strategies should prioritize younger nurses and those working longer hours or in high-intensity hospital settings. Policy-level solutions include:
- Supporting nurse mental health
- Offering flexible work arrangements
- Expanding nursing education pipelines
- Investing in support of RNs in hospital settings