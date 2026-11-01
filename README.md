# understanding-financial-markets-econometrics-ml
Research project applying econometrics and machine learning to analyze equity markets through time-series modeling, feature engineering, PCA, and predictive financial analytics.
# 📊 Financial Econometrics & Quantitative Finance Research Samples

[![Python](https://img.shields.io/badge/Python-3.10+-blue.svg)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange.svg)](https://jupyter.org/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()

> A collection of research-oriented projects demonstrating applications of **Financial Econometrics**, **Quantitative Finance**, **Machine Learning**, and **Statistical Modeling** using Python. The repository showcases reproducible research, publication-quality visualizations, and modern financial data analysis techniques.

---

## 👨‍💻 Author

**Rasheed Uthman**

M.Sc. Financial Engineering, WorldQuant University

Research Interests:

- Financial Econometrics
- Quantitative Finance
- Machine Learning
- Artificial Intelligence
- Financial Data Science
- Time Series Analysis
- Asset Pricing
- Computational Economics

---

# Repository Overview

This repository contains a collection of graduate-level quantitative finance and econometrics projects developed using Python.

The projects focus on analyzing macroeconomic and financial datasets through statistical modeling, feature engineering, machine learning, and visualization techniques.

Each project demonstrates the complete workflow:

- Data Collection
- Data Cleaning
- Statistical Analysis
- Model Development
- Diagnostic Testing
- Visualization
- Interpretation of Results

The goal is to build reproducible research suitable for academic research, graduate admissions, quantitative finance roles, and data science portfolios.

---

# Repository Structure

```
Writing-Research-Samples
│
├── Challenge 1
│   ├── Error Correction Model (ECM)
│   ├── Cointegration Analysis
│   ├── Stationarity Testing
│
├── Challenge 2
│   ├── Markov Regime Switching
│
├── Challenge 3
│   ├── Feature Engineering
│   ├── Principal Component Analysis (PCA)
│   ├── Technical Indicators
│   ├── Ridge Regression
│
├── Figures
│
├── Jupyter Notebook
│
└── README.md
```

---

# Project 1 — Error Correction Model (ECM)

## Objective

Investigate whether **Real GDP** and **Real Consumption** share a long-run equilibrium relationship despite both being non-stationary.

The project applies classical econometric methods to estimate an Error Correction Model (ECM), illustrating both long-run equilibrium and short-run adjustment dynamics.

---

## Methods Used

- Augmented Dickey-Fuller (ADF) Test
- Johansen Cointegration Test
- Ordinary Least Squares (OLS)
- Error Correction Model (ECM)
- Residual Diagnostics
- Normality Testing

---

## Visualizations

### Non-Stationary Series

Illustrates that both GDP and Consumption exhibit strong upward trends and are non-stationary.

<p align="center">
<img src="images/ecm_analysis.png" width="900">
</p>

---

### Long-Run Relationship

Shows the estimated equilibrium relationship between Real GDP and Real Consumption.

---

### First Differences

Transforms both variables into stationary series suitable for econometric modeling.

---

### Error Correction Term

Displays deviations from long-run equilibrium over time.

---

### Residual Diagnostics

Examines model assumptions including residual behavior and normality using Q-Q plots.

---

## Key Findings

✔ Strong evidence of cointegration

✔ Stable long-run relationship

✔ Error correction mechanism captures adjustment toward equilibrium

✔ Residuals exhibit approximately normal behavior

---

# Project 2 — Feature Engineering for Financial Markets

## Objective

Develop predictive financial features from historical stock prices for machine learning applications.

Historical market data are collected using **Yahoo Finance**.

Assets include:

- Apple
- Microsoft
- Google
- JPMorgan
- Johnson & Johnson
- ExxonMobil
- Walmart
- Procter & Gamble
- Disney
- Boeing

---

## Features Engineered

- Daily Returns
- Moving Average Ratio (MA5)
- Moving Average Ratio (MA20)
- Bollinger Band %
- Rolling Volatility

These features become the predictor variables used for forecasting future market returns.

---

# Project 3 — Bollinger Band Analysis

The repository includes implementation of Bollinger Bands for technical analysis.

The visualization demonstrates:

- Stock Price
- Upper Band
- Lower Band
- Bollinger Band %

<p align="center">
<img src="images/bollinger.png" width="850">
</p>

Applications include:

- Detecting overbought markets
- Detecting oversold markets
- Volatility measurement
- Momentum analysis

---

# Project 4 — Correlation Analysis

Understanding dependence among assets is critical for diversification.

A correlation matrix is constructed using daily stock returns.

<p align="center">
<img src="images/correlation.png" width="700">
</p>

The heatmap reveals:

- Positive relationships
- Negative relationships
- Diversification opportunities
- Market dependence

---

# Project 5 — Portfolio Performance

Portfolio performance is evaluated through cumulative normalized returns.

<p align="center">
<img src="images/cumulative_returns.png" width="850">
</p>

This visualization compares long-term growth across multiple stocks.

It provides insights into:

- Relative performance
- Portfolio diversification
- Return persistence
- Market leadership

---

# Project 6 — Distribution Analysis

Understanding the prediction target is essential before applying machine learning.

The repository examines the distribution of next-day S&P 500 returns.

<p align="center">
<img src="images/distribution.png" width="650">
</p>

The histogram illustrates:

- Mean behavior
- Variance
- Tail risk
- Approximate normality

---

# Project 7 — Principal Component Analysis (PCA)

High-dimensional financial datasets often contain redundant information.

This project applies PCA to compress engineered financial features while preserving most of the explained variance.

Workflow:

- Feature Standardization
- Bartlett's Test
- KMO Test
- PCA
- Explained Variance
- Ridge Regression Comparison

The analysis compares predictive performance using:

- Original Features
- PCA-Reduced Features

---

# Technologies

- Python
- Pandas
- NumPy
- Statsmodels
- Scikit-learn
- Matplotlib
- Seaborn
- yFinance
- Factor Analyzer
- Jupyter Notebook

---

# Skills Demonstrated

- Financial Econometrics
- Time Series Analysis
- Statistical Modeling
- Cointegration Analysis
- Error Correction Models
- Machine Learning
- Feature Engineering
- Principal Component Analysis
- Financial Visualization
- Data Science
- Quantitative Finance
- Python Programming

---

# Research Applications

The methods demonstrated in this repository are applicable to:

- Financial Economics
- Asset Pricing
- Portfolio Management
- Quantitative Trading
- Financial Risk Management
- Macroeconomic Forecasting
- Machine Learning in Finance
- Academic Research

---

# Future Work

Future extensions include:

- LSTM Neural Networks
- Transformer Models for Financial Forecasting
- Hidden Markov Models
- GARCH Volatility Models
- Vector Error Correction Models (VECM)
- Bayesian Econometrics
- Reinforcement Learning for Portfolio Optimization

---

# Citation

If you use this repository in your research, please cite:

```
Uthman, R. (2026).

Financial Econometrics & Quantitative Finance Research Samples.

GitHub Repository.

https://github.com/rasheey97-alt/Writing-Research-Samples
```

---

# Contact

**Rasheed Uthman**

GitHub:
https://github.com/rasheey97-alt

LinkedIn:
(Add your LinkedIn)

Email:
(Add your email)

---

⭐ If you find this repository useful, please consider giving it a star!
