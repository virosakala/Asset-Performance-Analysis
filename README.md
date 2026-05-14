# Asset Performance Analysis: Traditional vs. Digital Stores of Value

## Objective
This project executes a comparative historical analysis of two disparate asset classes: Gold (a traditional inflation hedge) and Bitcoin (a high-volatility digital asset). The objective is to extract live market data, normalize the price trajectories, and visualize their relative performance over a trailing 12-month window.

## Methodology & Technical Stack
The analysis relies on real-time API extraction rather than static or synthetic datasets.
* **Language:** Python 3
* **Data Ingestion:** `yfinance` (Yahoo Finance API integration)
* **Data Structuring:** `pandas` (Dataframe manipulation and normalisation)
* **Visualisation:** `matplotlib` (Comparative time-series plotting)

## Key Execution Steps
1. **API Extraction:** Downloaded daily closing prices for `GLD` and `BTC-USD` over 1 year.
2. **Data Normalisation:** Converted raw nominal prices into percentage growth (Base 100) to allow for an objective, 1:1 comparison of a $2,000 asset against a $60,000 asset.
3. **Visualisation:** Plotted the diverging trajectories to isolate volatility metrics and overall return profiles.

## Market Application
This model provides actionable intelligence for portfolio managers evaluating risk-adjusted returns and capital allocation strategies between stable commodities and high-beta digital assets.
