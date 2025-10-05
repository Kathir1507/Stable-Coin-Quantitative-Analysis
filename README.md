# Stable-Coin Quantitative Analysis

A comprehensive Python notebook analyzing the price stability, volatility, correlations, and risk performance of top stablecoins including USDT, USDC, DAI, BUSD, and FRAX. This project uses an index-based approach (PSPI), advanced statistical metrics, and data visualizations to rank and compare stablecoin stability. Designed for researchers, developers, and crypto enthusiasts interested in quantitative stablecoin metrics.

## Features

- **Automated Data Fetching:** Integrates Yahoo Finance and 12Data APIs for price data sourcing.
- **Price Stability Performance Index (PSPI):** Custom quantitative metric for stablecoin price stability assessment.
- **Volatility and Risk Analysis:** Annualized volatility, Value-at-Risk (VaR), regression models, and max drawdown.
- **Correlation Analysis:** Returns correlation matrix and visual heatmap for cross-stablecoin risk signaling.
- **Mechanism Hierarchy Comparison:** Aggregates findings by type (Fiat-backed, Crypto-backed, Hybrid, Algorithmic).
- **Clean Visualizations:** Time-series plots, bar charts, and heatmaps with clear Markdown interpretations.

## Core Results

- **USDT and USDC are most stable by PSPI, with lowest average deviations and volatility.**
- **DAI shows high stability despite being crypto-backed, while BUSD/FRAX show greater deviation and volatility.**
- **Stablecoin return correlations are close to zero, except for a slight negative USDT/USDC outlier.**
- **Regressions and hypothesis tests highlight clear mechanism performance hierarchies favoring fiat-backed and hybrid models.**

## Extending the Analysis

- Add new stablecoins by updating the `STABLECOINS` metadata dictionary.
- Experiment with additional quantitative risk metrics (e.g., Sharpe ratio, tail risk).
- Contribute improvements and suggestions via pull requests.
