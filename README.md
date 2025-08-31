# Quantitative Finance: Portfolio, Pricing, and Hedging Analysis

This repository contains a self-initiated summer project that explores **portfolio risk analysis**, **return distribution assumptions**, **option pricing**, and **hedging performance** under stochastic volatility.  
The project integrates real-world financial data with Python-based modeling and simulation techniques.

##  Project Overview
The project consists of four main parts:
1. **Portfolio Risk Analysis**  
   - Constructed minimum- and maximum-volatility portfolios using real stock data  
   - Computed covariance matrices and Sharpe Ratios to compare risk-return trade-offs  

2. **Return Distribution Tests**  
   - Tested whether daily log returns follow a normal distribution using statistical tests (e.g., Shapiro-Wilk, Jarque–Bera)  
   - Analyzed tail behavior and the impact of outlier removal  

3. **Option Pricing with Black–Scholes Model**  
   - Implemented the closed-form Black–Scholes formula for European call and put options  
   - Visualized option prices and Greeks (Delta, Vega, Theta) under different spot prices and maturities  

4. **Delta Hedging under Stochastic Volatility**  
   - Simulated stock paths using both random volatility models and the **Heston stochastic volatility model**  
   - Compared hedging performance under constant vs non-constant volatility assumptions

## Key Findings
- Minimum-volatility portfolios reduce drawdowns but limit upside potential; maximum-volatility portfolios carry higher risk and reward.  
- Daily log returns deviate from normality, exhibiting skewness and fat tails, challenging classical model assumptions.  
- Option Greeks provide critical insights into risk sensitivities, especially Delta and Vega.  
- Under stochastic volatility, delta hedging shows larger P&L dispersion, highlighting the limitations of constant-volatility models.

##  Tech Stack
- **Language:** Python 3  
- **Libraries:** NumPy, Pandas, Matplotlib, SciPy, yfinance  
- **Models:** Black–Scholes, Heston Stochastic Volatility, Monte Carlo Simulations  
