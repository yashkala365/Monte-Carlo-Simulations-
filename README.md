# Monte Carlo Option Pricing Engine

An institutional-style quantitative finance project that prices European and Asian call options using Monte Carlo simulation and compares the simulated option value with the analytical Black-Scholes model.

The project downloads live market data, estimates historical volatility, simulates thousands of future stock price scenarios using Geometric Brownian Motion (GBM), and visualizes the distribution of possible future prices.

---

## Project Overview

Option pricing is one of the core applications of quantitative finance.

This project demonstrates how stochastic simulation can be used to estimate the fair value of derivative contracts when closed-form analytical solutions may not always be available.

The notebook uses NVIDIA (NVDA) stock as the underlying asset and compares:

- Black-Scholes Analytical Pricing
- Monte Carlo European Option Pricing
- Monte Carlo Asian Option Pricing

---

## Features

- Live market data from Yahoo Finance
- Historical volatility estimation
- Black-Scholes analytical pricing model
- Monte Carlo simulation with 100,000 paths
- Geometric Brownian Motion (GBM) stock price simulation
- European Call Option Pricing
- Asian Call Option Pricing
- Terminal stock price distribution visualization
- Pricing comparison summary

---

## Financial Concepts Covered

- Derivative Pricing
- European Call Options
- Asian Options
- Risk-Neutral Valuation
- Stochastic Processes
- Geometric Brownian Motion (GBM)
- Monte Carlo Simulation
- Historical Volatility
- Discounted Expected Payoff
- Black-Scholes Model

---

## Workflow

```
Download Historical Market Data
            │
            ▼
Estimate Annualized Volatility
            │
            ▼
Calculate Black-Scholes Price
            │
            ▼
Generate Random Price Paths
using Geometric Brownian Motion
            │
            ▼
Monte Carlo Simulation
(100,000 Simulations)
            │
            ▼
Calculate Option Payoffs
            │
            ▼
Discount Expected Payoff
            │
            ▼
European Option Price
            │
            ▼
Asian Option Price
            │
            ▼
Visualize Price Paths & Distribution
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- SciPy
- yFinance
- Google Colab

---

## Model Assumptions

- Geometric Brownian Motion
- Constant volatility
- Constant risk-free interest rate
- Log-normal stock price distribution
- No dividends
- Frictionless markets
- Efficient markets

---

## Visualizations

The notebook generates:

### GBM Price Paths

Simulates multiple possible future stock price trajectories over one year.

---

### Terminal Price Distribution

Histogram showing the probability distribution of simulated stock prices at option maturity.

---

### Pricing Summary

Compares:

- Spot Price
- Strike Price
- Historical Volatility
- Black-Scholes Price
- Monte Carlo Price
- Asian Option Price

---

## Example Output

| Metric | Value |
|---------|-------|
| Underlying | NVDA |
| Option Type | European Call |
| Monte Carlo Simulations | 100,000 |
| Time Horizon | 1 Year |
| Black-Scholes Price | Calculated |
| Monte Carlo Price | Calculated |
| Asian Option Price | Calculated |

---

## Installation

Clone the repository

```bash
git clone https://github.com/yourusername/Monte-Carlo-Option-Pricing.git
```

Install dependencies

```bash
pip install -r requirements.txt
```

Run the notebook

```bash
jupyter notebook
```

or open directly in Google Colab.

---

## Future Improvements

- American Option Pricing
- Barrier Options
- Lookback Options
- Variance Reduction Techniques
- Antithetic Sampling
- Control Variates
- Quasi Monte Carlo Methods
- GPU Acceleration
- Greeks Estimation (Delta, Gamma, Vega, Theta)
- Interactive Streamlit Dashboard

---

## Skills Demonstrated

- Quantitative Finance
- Financial Engineering
- Derivatives Pricing
- Monte Carlo Methods
- Stochastic Modeling
- Black-Scholes Model
- Numerical Methods
- Python Programming
- Data Analysis
- Financial Data Processing
- Scientific Computing

---

## Author

**Yash**

Aspiring Quantitative Researcher | Financial Engineer | Python Developer

```

## ⭐ Recruiter Highlights

- Uses **live market data** instead of static datasets.
- Implements **both analytical (Black–Scholes)** and **numerical (Monte Carlo)** pricing approaches, allowing direct comparison.
- Includes **Geometric Brownian Motion path simulation**, **terminal price distribution**, and **Asian option pricing**, demonstrating knowledge beyond basic option valuation.
- Organized as an institutional-style workflow from data acquisition through simulation, valuation, visualization, and summary, making it suitable as a portfolio project for quantitative finance and financial engineering roles.
