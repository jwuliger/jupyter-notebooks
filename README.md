# Financial Analysis & Prediction Notebooks

This repository contains Jupyter notebooks related to financial analysis and price prediction. Each notebook focuses on a unique aspect of financial data processing, visualization, and prediction.

## 1. [Support and Resistance Analysis](./indicators/support-resistance.ipynb)
This notebook provides methods to:
- Import necessary libraries.
- Fetch financial data using the `ccxt` library.
- Define functions to determine support and resistance.
- Identify support and resistance levels.
- Plot a candlestick chart with the identified support and resistance lines.

## 2. [TPO Market Profile Chart](./indicators/tpo-market-profile-chart.ipynb)
This notebook delves into the creation of a TPO (Time Price Opportunity) Market Profile chart. Topics covered include:
- Fetching OHLCV (Open, High, Low, Close, Volume) data.
- Saving data to a CSV file.
- Calculating the Average True Range (ATR).
- Determining the overall price range.
- Creating price intervals.
- Plotting symbols for the TPO chart.
- Calculating the Point of Control (POC), Value Area Low (VAL), and Value Area High (VAH).
- Identifying single prints in the chart.
- Visualizing the TPO chart using the `Plotly` library.

## 3. [Bitcoin Price Prediction using LSTM](./predictions/basic-lstm-btc-price.ipynb)
A notebook that employs a basic LSTM (Long Short-Term Memory) neural network to predict Bitcoin (BTC) prices. The steps covered are:
- Data Collection.
- Data Preprocessing & Feature Engineering.
- Preparing the dataset specifically for LSTM.
- Building the LSTM model.
- Running the logic flow for prediction.

---

**Note**: Ensure you have the required libraries and dependencies installed before running the notebooks.
