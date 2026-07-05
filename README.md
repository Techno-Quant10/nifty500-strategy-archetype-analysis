# Quantitative Comparison of Trend Following, Mean Reversion & Breakout Trading Strategies Across the Nifty 500

## Overview

This repository contains the complete research notebook accompanying my analysis comparing three classical trading strategy archetypes across the Nifty 500 universe:

- Trend Following (MACD)
- Mean Reversion
- Bollinger Band Breakout

The objective was to compare how different strategy families generate returns through their unique statistical characteristics rather than relying on a single headline metric such as win rate.

---

## Dataset

- **Universe:** 493 Nifty 500 Stocks
- **Data Source:** Yahoo Finance (yfinance)
- **Study Period:** 2000 – 2026

---

## Methodology

The research pipeline includes:

- Historical data collection and preprocessing
- Technical indicator computation
- Trade generation for all three strategies
- Trade-level performance statistics
- Long vs Short analysis
- Winsorized robustness analysis
- Tail-risk analysis
- Holding-period analysis
- Strategy comparison using institutional performance metrics
- Quantitative visualizations

To improve robustness, the analysis incorporates trade-quality filters, holding-period constraints, percentile-based tail analysis, and Winsorized statistics to reduce the influence of extreme observations while preserving the underlying return distribution.

---

## Performance Metrics

The strategies are compared using metrics including:

- Win Rate
- Profit Factor
- Payoff Ratio
- Expectancy
- Mean & Median Returns
- Holding Period
- Tail Risk
- Return Distribution
- Skewness
- Kurtosis

---

## Technologies Used

- Python
- Pandas
- NumPy
- SciPy
- Matplotlib
- yfinance
- tqdm

---

## Repository Contents

- `Quantitative_Comparison_of_Trading_Strategies.ipynb` — Complete research notebook with code, analysis, statistics, and visualizations.

---

## Disclaimer

This repository is intended solely for quantitative research and educational purposes. It does not constitute investment advice or a recommendation to buy or sell any financial instrument.

---

**Author:** Navon Shapurkar
