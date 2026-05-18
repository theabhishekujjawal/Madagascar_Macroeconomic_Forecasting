# Madagascar Macroeconomic Forecasting

![Python](https://img.shields.io/badge/Python-3.8+-blue)
![Domain](https://img.shields.io/badge/Domain-Econometrics-green)
![Models](https://img.shields.io/badge/Models-OLS%20%7C%20ARIMA%20%7C%20VAR-orange)
![Data](https://img.shields.io/badge/Data-World%20Bank-purple)

> Econometric analysis and GDP forecasting for Madagascar using OLS, ARIMA, ARIMAX, and VAR models with impulse response and variance decomposition analysis.

---

## Project Overview

This repository contains a comprehensive econometric analysis and macroeconomic forecasting framework for Madagascar. Using historical World Bank data, the project applies multiple time-series modelling techniques to identify the key drivers of Madagascar's economy and forecast Gross Domestic Product (GDP).

## Methodology

### Stationarity & Cointegration
- Augmented Dickey-Fuller (ADF) tests for unit root detection
- Johansen Cointegration tests for long-run equilibrium relationships

### Models Implemented

| Model | Type | Description |
|-------|------|-------------|
| **OLS** | Cross-sectional | Multivariate regression with robust standard errors |
| **ARIMA** | Univariate | AutoRegressive Integrated Moving Average |
| **ARIMAX** | Multivariate | ARIMA with exogenous macroeconomic regressors |
| **VAR** | System | Vector Autoregression for dynamic multi-variable analysis |

### Diagnostics
- Variance Inflation Factor (VIF) for multicollinearity detection
- Ljung-Box tests for residual autocorrelation
- Model selection via AIC, BIC, R², and RMSE

### Shock Analysis
- **Impulse Response Functions (IRF)**: Dynamic propagation of macroeconomic shocks
- **Forecast Error Variance Decomposition (FEVD)**: Contribution of each variable to forecast uncertainty over time

## Repository Structure

```
├── Madagascar_Macroeconomic_Forecasting_Advanced.ipynb   # Full econometric pipeline
├── madagascar_worldbank_data.csv                         # Raw World Bank dataset
├── *.csv                                                 # Generated output tables
└── README.md
```

## How to Run

```bash
git clone https://github.com/theabhishekujjawal/Madagascar_Macroeconomic_Forecasting.git
cd Madagascar_Macroeconomic_Forecasting
pip install pandas numpy statsmodels matplotlib seaborn
jupyter notebook Madagascar_Macroeconomic_Forecasting_Advanced.ipynb
```

Run cells sequentially to reproduce the data processing, model training, and shock analysis.

## Requirements

- Python 3.8+
- pandas, numpy, statsmodels, matplotlib, seaborn
- Jupyter Notebook

## Academic Context

Completed as part of the MSc Quantitative Finance programme at UCD Michael Smurfit Graduate Business School (2025–2026).

## Author

**Abhishek Ujjawal** — MSc Quantitative Finance, UCD Michael Smurfit Graduate Business School

[LinkedIn](https://linkedin.com/in/theabhishekujjawal) · [GitHub](https://github.com/theabhishekujjawal) · [Portfolio](https://theabhishekujjawal.github.io/Bio)