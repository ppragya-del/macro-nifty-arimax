# Macro-Financial Time-Series Analysis (India, 2014–2024)

This project builds a monthly macro–financial panel for India (Nifty 50, CPI inflation, RBI repo rate, INR/USD) and estimates ARIMAX models for Nifty 50 returns.

## Data
- Nifty 50 monthly closes (Apr 2014–Mar 2024)
- All-India CPI inflation (CPI-IW)
- RBI repo rate (policy rate)
- INR/USD exchange rate

## Methods
- Data cleaning and monthly panel construction in pandas
- Exploratory plots, summary statistics, correlations, OLS level model
- Unit-root tests (ADF) and diagnostics
- ARIMA/ARIMAX modelling of Nifty 50 monthly log-returns with macro variables as exogenous regressors

## Key findings
- Nifty 50 returns are stationary, while index levels are non-stationary.
- Macro variables in levels are highly persistent and work as exogenous drivers in ARIMAX.
- ARIMAX residual diagnostics show no serial correlation and well-behaved errors, while level OLS residuals are strongly autocorrelated.
