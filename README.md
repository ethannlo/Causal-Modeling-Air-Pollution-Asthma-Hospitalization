# Causal Modeling: Air Pollution & Asthma Hospitalization

## Table of Contents
- [Overview](#overview)
- [Datasets](#datasets)
- [Methodology](#methodology)
- [Results](#results)
- [Future Work](#future-work)
- [Installation](#installation)

## Overview
This project investigates the causal relationship between air pollution and asthma-related hospitalizations using **causal inference techniques**. By integrating and analyzing large-scale **healthcare and environmental datasets** from the **CDC, KFF, and EPA**, we aim to quantify the impact of air pollution on public health.  

The study employs **logistic regression, inverse probability weighting (IPW), and statistical hypothesis testing** to control for confounding factors and improve model accuracy. **Data visualizations** and insights derived from this research can help policymakers and healthcare professionals better understand regional asthma trends.  

## Datasets
The analysis integrates data from multiple sources, totaling over 200M observations, including:
- **CDC (Centers for Disease Control and Prevention)** - Health statistics
- **KFF (Kaiser Family Foundation)** - Healthcare accessibility and socioeconomic data
- **EPA (Environmental Protection Agency)** - Air pollution levels (PM2.5, NO₂, CO, etc.)

## Methodology
- **ETL Pipeline:** Data cleaning, normalization, and integration across multiple sources.
- **Causal Inference Modeling:** Built using logistic regression (Scikit-learn), incorporating **Inverse Probability Weighting (IPW)** to control for confounders such as age, socioeconomic status, and healthcare access.
- **Statistical Analysis:**
  - T-tests and power analysis (SciPy & statsmodels) to evaluate statistical significance.
- **Visualizations:** Analyze regional trends and hospitalization patterns with Seaborn.

## Results
The model demonstrates a statistically significant relationship between increased pollution levels and higher asthma hospitalization rates, with confounder adjustments improving model accuracy. 

## Future Work
- Expand dataset with additional environmental and demographic factors.
- Improve model accuracy with deep learning techniques.
- Develop a real-time dashboard for monitoring pollution-related health risks.

## Installation
To run this project, ensure you have the following dependencies installed:

```bash
pip install pandas numpy scikit-learn seaborn statsmodels scipy jupyter
```
