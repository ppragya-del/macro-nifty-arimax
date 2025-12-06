# Macro-Financial Time-Series Analysis (India, 2014–2024)

This project builds a monthly macro–financial panel for India (Nifty 50, CPI inflation, RBI repo rate, INR/USD) and estimates ARIMAX models for Nifty 50 returns.

# Objective

To analyze how key macroeconomic variables — inflation, repo rate, and INR/USD exchange rate — influence Nifty index returns, and to develop an ARIMAX forecasting model to study direction, sensitivity, and short-term trend patterns.

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

## Key Observations

Repo rate exhibited a directional impact on Nifty index returns, where phases of tightening were associated with short-term moderation in index movement, reflecting cautious investor sentiment.

Inflation showed signs of a lagged effect, suggesting that price-level changes gradually influence market confidence and corporate earnings expectations rather than affecting index volatility immediately.

The INR/USD exchange rate indicated a sensitivity pattern, where currency depreciation aligned with negative directional shifts due to concerns around foreign capital flows and import cost pressures.

The ARIMAX model demonstrated a better fit for capturing directional trends compared to a simple baseline model, although forecast magnitude deviations highlight the inherent uncertainty of macro-driven predictions.

The results reinforce that macro variables act as signals rather than standalone predictors, and interpretation works best when combined with broader economic context and policy developments.
