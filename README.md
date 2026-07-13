# Options Trading and Derivatives Analysis

A Python-based quantitative finance project for pricing European options, computing option Greeks, visualizing payoff structures, and evaluating multi-leg options strategies under varying market conditions using the Black–Scholes model.

---

## Overview

This project implements a modular framework for analyzing options and common derivatives strategies. It combines analytical pricing models with payoff visualization to study risk-return characteristics, option sensitivities, and the behavior of multi-leg portfolios across different market scenarios.

The project was developed as a self-learning exercise to strengthen understanding of derivatives pricing, quantitative risk management, and computational finance.

---

## Features

- Black–Scholes pricing for European Call and Put options
- Analytical computation of option Greeks
  - Delta
  - Gamma
  - Vega
  - Theta
  - Rho
- Payoff visualization for individual options
- Multi-leg strategy construction
- Profit/Loss analysis across expiration prices
- Strategy comparison under varying volatility assumptions
- Interactive parameter experimentation

---

## Implemented Strategies

- Long Call
- Long Put
- Covered Call
- Protective Put
- Bull Call Spread
- Bear Put Spread
- Long Straddle
- Long Strangle

---

## Mathematical Models

### Option Pricing

- Black–Scholes Model
- Risk-neutral valuation
- Log-normal asset price assumption

### Greeks

- Delta
- Gamma
- Vega
- Theta
- Rho

---

## Project Structure

```text
Options-Trading-Analysis/
│
├── main.py
├── black_scholes.py
├── greeks.py
├── strategies.py
├── payoffs.py
├── visualization.py
├── utils.py
│
├── data/
│   └── sample_option_chain.csv
│
├── results/
│   ├── payoff_plots/
│   ├── strategy_comparisons/
│   └── greek_visualizations/
│
├── requirements.txt
└── README.md
```

---

## Technologies Used

- Python 3.11
- NumPy
- Pandas
- SciPy
- Matplotlib

---

## Example Inputs

```text
Underlying Price : 100
Strike Price     : 105
Risk-free Rate   : 5%
Volatility       : 22%
Time to Expiry   : 0.50 years
```

---

## Sample Output

```text
Call Price : 4.81
Put Price  : 7.25

Delta : 0.43
Gamma : 0.024
Theta : -6.12
Vega  : 27.84
Rho   : 18.91
```

---

## Performance Evaluation

The framework was used to compare over **30 option strategy configurations** under varying:

- Volatility levels
- Strike combinations
- Time to expiry
- Underlying price movements

Generated outputs include:

- Payoff diagrams
- Profit/Loss curves
- Comparative risk-return profiles

---

## Learning Outcomes

Through this project, I gained practical experience with:

- Computational implementation of the Black–Scholes model
- Numerical computation of option Greeks
- Construction of multi-leg option strategies
- Quantitative risk analysis
- Financial data visualization
- Modular software design in Python

---

## Future Improvements

- American option pricing using Binomial Trees
- Monte Carlo option pricing
- Implied volatility solver
- Real-time option chain integration
- Historical options backtesting
- Interactive dashboard using Streamlit

---

## References

1. John C. Hull, *Options, Futures, and Other Derivatives*
2. Fischer Black & Myron Scholes, *The Pricing of Options and Corporate Liabilities* (1973)
3. Sheldon Natenberg, *Option Volatility & Pricing*

---

## License

This project is intended for educational and research purposes.
