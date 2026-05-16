# Stock Price Prediction

Tesla (TSLA) stock price prediction using hand-engineered features 
and linear models, built as part of Siraj Raval's Machine Learning 
MasterClass, September 2019.

## Feature Engineering

Four feature sets designed from first principles and benchmarked 
against a lag baseline:

- **Feature A** — previous week's closing prices (5-day window)
- **Feature B** — 3-day average daily volatility (High - Low)
- **Feature C** — 10-day moving average
- **Feature D** — overnight gap between previous close and current open

Each feature set evaluated against Linear Regression, Ridge, and 
Lasso, with MAE, MSE, and RMSE reported for each combination.

## Dataset

Yahoo Finance TSLA data, September 2016 to September 2019, via 
pandas-datareader. 60/40 train/test split.

## Stack

Python, pandas, scikit-learn, matplotlib

## Status

Completed for bootcamp submission, September 2019. Not maintained.
The `# Reticulating splines...` comment remains accurate.
