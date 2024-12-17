# NIFTY-50-Options-Pricing-using-Black-Scholes-and-Monte-Carlo-Simulation

NIFTY 50 Options Pricing using Black-Scholes and Monte Carlo Simulation
This project implements European Call Option pricing using the Black-Scholes model and Monte Carlo simulations under a risk-neutral framework. The project focuses on options based on the NIFTY 50 Index (India’s benchmark stock index), retrieving real-world data and analyzing volatility to estimate option prices.

Features
Fetch Real-Time Market Data:
Retrieve historical NIFTY 50 price data from Yahoo Finance.

Volatility Calculation:
Estimate the annualized historical volatility based on daily log returns.

European Call Option Pricing:

Black-Scholes Analytical Solution: Analytical formula for European options.
Monte Carlo Simulation: Simulate stock price paths under the risk-neutral measure to estimate option prices.
Visualizations:

NIFTY 50 historical price trends and log returns.
Option prices for different strike prices and maturities.

Technologies Used:

Python: Core programming language.
Libraries:
yfinance: Fetch financial market data.
numpy: Numerical computations.
pandas: Data manipulation and analysis.
scipy: Black-Scholes implementation using statistical functions.
matplotlib: Visualizations.

Project Workflow
1. Data Collection
Fetch historical NIFTY 50 index data for the last year using yfinance.
Calculate daily log returns and estimate annualized volatility:
𝜎=StdDev(Log Returns)×252
 
2. Option Pricing
![image](https://github.com/user-attachments/assets/88dafddf-216f-4f27-906e-2c9fc1283974)
