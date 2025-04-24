# LeanHogs_LiveCattle
Econometric Analysis of Lean Hogs and Live Cattle Futures Prices

This project conducts an econometric analysis of financial time series data for Lean Hogs (LH) and Live Cattle (LC) futures prices, alongside the Global Food Price Index (PFOODINDEXM), using Gretl. The dataset covers daily and monthly prices from NASDAQ and Federal Reserve Economic Data, spanning February 2016 to December 2023 for monthly data and March 2019 to February 2021 for daily data.
Key Features:
Descriptive Statistics: Analysis of daily and monthly prices and logarithmic returns, highlighting volatility, skewness, and kurtosis. Lean Hogs show higher volatility compared to Live Cattle.

Stationarity Tests: Augmented Dickey-Fuller (ADF) tests confirm non-stationarity of price levels (I(1)) but stationarity of logarithmic returns (I(0)) for LH, LC, and PFOODINDEXM.

Cointegration Analysis: Tests reveal a long-term relationship between LH and LC prices, with a statistically significant cointegrating equation explaining 18% of LH price variability.

VAR Modeling: A Vector Autoregression (VAR) model with one lag examines the transmission of shocks. Granger causality tests suggest limited short-term influence between variables, with impulses dissipating within six months.

Single-Factor Models: OLS estimation models assess the impact of PFOODINDEXM on LH and LC returns, showing statistical significance but low explanatory power (R²: 0.08 for LH, 0.07 for LC).

Autocorrelation Analysis: ACF, PACF, and Ljung-Box tests indicate significant autocorrelations in returns, suggesting potential for autoregressive modeling.

Data Sources:
NASDAQ: Lean Hogs and Live Cattle futures prices.

Federal Reserve Economic Data: Global Food Price Index (PFOODINDEXM).

Tools:
Gretl: Used for all econometric computations, including descriptive statistics, ADF tests, cointegration, VAR modeling, and OLS estimation.


