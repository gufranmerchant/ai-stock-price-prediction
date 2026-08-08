# AI Stock Price Prediction

LSTM-based time-series forecasting model predicting next-day stock closing prices from
historical market data.

## Approach

- Collected and preprocessed financial data using `yfinance`, `pandas`, and
  `MinMaxScaler`, building supervised learning sequences from historical price windows.
- Implemented a multi-layer LSTM architecture (TensorFlow/Keras) with dropout
  regularisation to reduce overfitting and improve stability on unseen data.
- Evaluated performance by generating real-time predictions and visualising results with
  Matplotlib to track trend accuracy against actuals.

## Stack

Python · TensorFlow/Keras · Pandas · yfinance · Matplotlib · scikit-learn (MinMaxScaler)

## Status

Proof-of-concept model, not intended as investment advice. Built to explore time-series
forecasting architecture and evaluation methodology for sequential financial data.

## Run locally

```bash
pip install -r requirements.txt
python predicting_stock_prices.py
```
