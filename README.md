# 📈 Determinants of Infant Mortality in Minas Gerais: A Panel Data Analysis

> **An econometric study on the socioeconomic factors impacting infant mortality across municipalities in Minas Gerais, Brazil.**

[![Stata](https://img.shields.io/badge/Analysis-Stata-blue)](https://www.stata.com/)
[![Status](https://img.shields.io/badge/Status-Completed-success?style=for-the-badge)]()

## ⚠️ Important Disclaimer regarding Source Code
> **The Stata do-files were intentionally omitted from this repository as the data cleaning and transformations were performed directly on the `.dta` file without a script backup at the time. However, all essential methodological steps, variable constructions, and econometric outputs are fully documented and available in the [attached PDF report](infant-mortality-panel-data.pdf).**

---

## 🎯 Project Overview

This research explores the primary factors influencing infant mortality rates in the state of Minas Gerais. By utilizing a robust dataset of municipal indicators, the study aims to identify how variables such as education, sanitation, and economic performance correlate with early childhood health outcomes.

---

## 🛠️ Methodology & Econometric Approach

The project employs advanced econometric techniques to handle the multidimensional nature of the data (municipalities over time).

### 1. Models Implemented
* **Pooled OLS:** Used as a baseline for linear regression analysis.
* **Fixed Effects (Within Transformation):** To control for time-invariant unobserved heterogeneity specific to each municipality.
* **Random Effects (GLS/MQG):** To account for potential serial correlation and provide efficient estimates when appropriate.

### 2. Statistical Validation (Tests)
To ensure the reliability of the results, the following tests were conducted:
* **Breusch-Pagan Lagrange Multiplier:** To choose between Pooled OLS and Random Effects.
* **Hausman Test:** To determine the consistency of Random Effects versus the robustness of Fixed Effects.

---

## 📊 Key Variables & Indicators

The analysis integrates data from multiple sources (IBGE, DATASUS, etc.), focusing on:
* **Infant Mortality:** Mortality rates (Dependent Variable).
* **Education:** Average years of schooling (Adults 25+).
* **Economic:** Municipal GDP and indebtedness levels.
* **Social:** Unemployment rates and local infrastructure.

---

## 📈 Summary of Findings

The results highlight that:
1. **Education** remains a crucial factor; higher levels of schooling for adults significantly correlate with lower infant mortality rates due to better preventive care.
2. **Public Policy:** The study suggests that government awareness programs and infrastructure investments are vital for reducing mortality trends in Minas Gerais.

---

## 👥 Author
* **Lauro Aguiar**

---
**This is an academic and educational project developed as part of the Econometrics III coursework at Ibmec.**
