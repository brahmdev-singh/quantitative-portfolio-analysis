# quantitative-portfolio-analysis

Quantitative analysis of a 10-asset equity universe using MPT, CAPM, and BSM models in Python.

# Quantitative Equity Analysis & Option Pricing

**Portfolio Optimization, Risk Decomposition (CAPM), and BSM Modeling**

## 📌 Project Overview

This project provides a comprehensive quantitative analysis of a 10-asset equity universe (including AVGO, COP, CMG, etc.) over a 10-year horizon (2015–2025). It bridges financial economic theory with computational finance using Python.

The analysis is divided into four core pillars:

1. **Modern Portfolio Theory (MPT):** Constructing a Sharpe-Ratio Maximized portfolio.
2. **Asset Pricing:** Evaluating systematic vs. idiosyncratic risk using the Capital Asset Pricing Model (CAPM).
3. **Risk Management:** Calculating Value at Risk (VaR) at individual and portfolio levels.
4. **Derivative Pricing:** Implementing the Black-Scholes-Merton (BSM) formula for European options.

## 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:** `pandas`, `numpy`, `matplotlib`, `scipy.optimize`, `statsmodels`, `yfinance`
- **Environment:** Jupyter Notebook

## 📊 Key Features

### 1. Sharpe Ratio Optimization

- Automated data retrieval for 10 tickers via Yahoo Finance.
- Calculation of annualized returns, volatility, and the "Tangency Portfolio."
- Visualization of the **Efficient Frontier** and Capital Allocation Line (CAL).

### 2. CAPM & Variance Decomposition

- Running OLS regression against the S&P 500.
- Extracting Alpha and Beta metrics.
- Breaking down risk into Systematic (Market) and Idiosyncratic (Firm-specific) components.

### 3. Value at Risk (VaR)

- Historical simulation of VaR at the 95% confidence level.
- Analysis of the **Diversification Benefit**—quantifying how much risk is "canceled out" by the portfolio structure.

### 4. Black-Scholes-Merton Implementation

- Pricing European Call and Put options.
- Analysis of the Greeks ($d_1$ and $d_2$) and the impact of volatility on pricing.

## 📂 Repository Structure

- `analysis.ipynb`: The core Python implementation.
- `report.pdf`: A formal academic write-up of the findings and economic interpretations.
- `requirements.txt`: List of necessary Python packages.

## 📈 Sample Results

_(Tip: Insert a screenshot here of your Efficient Frontier plot or your Correlation Heatmap from the notebook)_

---

**Author:** Brahmdev Singh  
**Academic Context:** MSc Fintech, University of Galway
