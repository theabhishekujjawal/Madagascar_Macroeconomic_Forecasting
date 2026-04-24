# Madagascar Macroeconomic Forecasting

## 📌 Project Overview
This repository contains a comprehensive econometric analysis and macroeconomic forecasting model for Madagascar. Using historical World Bank data, this project applies advanced time-series modeling techniques to understand the key drivers of Madagascar's economy and forecast the Gross Domestic Product (GDP).

## 🚀 Key Features and Methodologies
- **Exploratory Data Analysis & Descriptive Statistics**: Detailed summary and correlation checks of macroeconomic variables.
- **Stationarity & Cointegration Tests**: Applications of Augmented Dickey-Fuller (ADF) tests and Johansen Cointegration checks to ensure data validity.
- **Time-Series Models**:
  - **OLS (Ordinary Least Squares)** Regression with robust standard errors.
  - **ARIMA (AutoRegressive Integrated Moving Average)** for univariate forecasting.
  - **ARIMAX** for multivariate forecasting with exogenous variables.
  - **VAR (Vector Autoregression)** modeling for dynamic system analysis.
- **Advanced Diagnostics**:
  - Variance Inflation Factor (VIF) for multicollinearity.
  - Ljung-Box tests for ARIMA residuals.
- **Shock Analysis**: 
  - **Impulse Response Functions (IRF)**: Visualizing dynamic shock propagation across the economy.
  - **Forecast Error Variance Decomposition (FEVD)**: Quantifying the drivers of forecast errors over time.

## 📂 Repository Structure
- `Madagascar_Macroeconomic_Forecasting_Advanced.ipynb` - The primary Jupyter Notebook containing the full end-to-end econometric pipeline, training, and analysis.
- `madagascar_worldbank_data.csv` - The raw World Bank dataset used for the analysis.
- `*.csv` files - Generated output tables containing coefficients, model statistics, selection criteria, stationary tests, and diagnostics.

## 📊 Results Summary
The analysis evaluates multiple models based on $R^2$, RMSE, AIC, and BIC to determine the most robust forecasting approach for Madagascar's GDP. (Detailed coefficients and diagnostic checks can be found in the respective CSV output files).

## 🛠️ Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/theabhishekujjawal/Madagascar_Macroeconomic_Forecasting.git
   ```
2. Open the main notebook:
   ```bash
   jupyter notebook Madagascar_Macroeconomic_Forecasting_Advanced.ipynb
   ```
3. Run the cells sequentially to reproduce the data processing, model training, and shock analysis steps.

## 📝 Requirements
- Python 3.8+
- Jupyter Notebook
- `pandas`, `numpy`, `statsmodels`, `matplotlib`, `seaborn`

---
*Created by [theabhishekujjawal](https://github.com/theabhishekujjawal).*