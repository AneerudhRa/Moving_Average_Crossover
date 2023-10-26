# "Moving Average Crossover Strategy"


## Overview

This repository contains a Python script to visualize Buy/Sell signals for a forex pair EUR/USD and applying the Moving Average Crossover strategy. The strategy is based on two moving averages: a short-term (10-day) moving average and a long-term (50-day) moving average.

## Strategy Explanation

When the short-term moving average crosses above the long-term moving average, a buy signal is generated, suggesting it might be a good time to purchase the stock/currency. Conversely, when the short-term moving average crosses below the long-term moving average, a sell signal is generated, suggesting it might be a good time to sell the stock/currency.

## Libraries Used

- `yfinance`: For fetching the stock data.
- `pandas`: For data manipulation.
- `numpy`: For numerical operations.
- `matplotlib`: For visualizing the stock prices and Buy/Sell signals.


## Disclaimer

This is a simple strategy for visualization purposes and may not be optimal for real-world trading. Always conduct thorough research and/or consult with a financial advisor before making any trading decisions.
