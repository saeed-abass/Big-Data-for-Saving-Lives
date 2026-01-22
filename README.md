# Big Data for Saving Lives: Mental Health Stress Risk Analysis

This project analyzes large-scale self-reported mental-health survey data to:
- identify psychological risk patterns,
- support workplace resource allocation, and
- predict individuals at elevated risk of **Increasing Stress**.


## Project Goals

- Explore population-level patterns in self-reported mental-health indicators
- Visualize key distributions (e.g., gender, country representation, isolation duration)
- Examine associations between lifestyle/work factors and increasing stress
- Train and evaluate a predictive model to support outreach prioritization

## Dataset

The dataset is sourced from Kaggle:

**Mental Health Dataset** — Alam, S. (2023)  
https://www.kaggle.com/datasets/alamshihab075/mental-health-dataset

> Note: This is self-reported survey data and may contain reporting bias, missing values, and representational imbalance.

## Methodology Summary

Key steps used in this project:

1. **Data Cleaning & Preprocessing**
   - Standardized column naming
   - Mapped binary/categorical fields into consistent formats
   - Handled missing values conservatively
   - Retained features with sufficient completeness for modelling

2. **Exploratory Data Analysis (EDA)**
   - Statistical summaries
   - Distribution plots (e.g., gender and country distribution)
   - Correlation analysis and heatmaps for feature relationships

3. **Predictive Modelling**
   - Baseline **Logistic Regression**
   - Train/test split approach
   - Performance evaluated using:
     - Accuracy
     - ROC-AUC
     - Precision / Recall / F1-score
   - Coefficient visualization for interpretability

## Ethical Use Notice

This repository provides analytical and modelling tools for educational and research purposes only.

- Do **not** treat outputs as clinical diagnosis.
- Use strong privacy protections and lawful data handling practices.
- Avoid deployment without fairness auditing, stakeholder review, and robust validation.

## How to Cite / Credit This Work (Required)

If you use this work in a report, project, publication, or derived software, you **must credit the author(s)** clearly.

Example citation:

> Abass Saeed Mohammed, "Big Data for Saving Lives: Analyzing Self-Reported Patient Data to Identify Risk Patterns, Optimize Support, and Predict Increasing Stress", 2025.

## Authors

- **Abass Saeed Mohammed**

## License

This project is licensed under the **Attribution License (Custom)** — you may use, modify, and distribute the work **provided that you reference the author(s)**. See the `LICENSE` file for details.
