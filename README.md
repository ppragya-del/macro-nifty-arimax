{\rtf1\ansi\ansicpg1252\cocoartf2820
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww33700\viewh20520\viewkind0
\pard\tx720\tx1440\tx2160\tx2880\tx3600\tx4320\tx5040\tx5760\tx6480\tx7200\tx7920\tx8640\pardirnatural\partightenfactor0

\f0\fs24 \cf0 # Macro-Financial Time-Series Analysis (India, 2014\'962024)\
\
This project builds a monthly macro\'96financial panel for India (Nifty 50, CPI inflation, RBI repo rate, INR/USD) and estimates ARIMAX models for Nifty 50 returns.\
\
## Data\
\
- Nifty 50 monthly closes (Apr 2014\'96Mar 2024)\
- All-India CPI inflation (CPI-IW)\
- RBI repo rate (policy rate)\
- INR/USD exchange rate\
\
## Methods\
\
- Data cleaning and monthly panel construction in pandas\
- Exploratory plots, summary statistics, correlations, OLS level model\
- Unit-root tests (ADF) and diagnostics\
- ARIMA/ARIMAX modelling of Nifty 50 monthly log-returns with macro variables as exogenous regressors\
\
## Key findings\
\
- Nifty 50 returns are stationary; index levels are non-stationary.\
- Macro variables in levels are highly persistent and work as exogenous drivers in ARIMAX.\
- ARIMAX residual diagnostics show no serial correlation and well-behaved errors, while level OLS residuals are strongly autocorrelated.\
}