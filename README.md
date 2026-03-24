# Stock Price Prediction Model
This project implements a regression-based time-series forecasting model to predict stock prices using historical financial data. The goal is to analyze trends and evaluate how well machine learning models can capture stock price movement.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- yfinance

## Features
- Moving averages (5-day and 10-day)
- Daily returns (price momentum)
- Rolling volatility (risk measurement)

## Model
- Linear Regression model trained on time-series data (no shuffling)

## Methodology
1. Collected historical stock data using yfinance  
2. Engineered features such as moving averages, returns, and volatility  
3. Created a target variable representing the next day's closing price  
4. Split data into training and testing sets while preserving time order  
5. Trained a regression model to predict future prices  
6. Evaluated model performance using MAE, RMSE, and R²  

## Results
The model generates predictions for next-day stock prices and compares them to actual values. Performance is evaluated through error metrics and visualized using line plots of predicted vs actual prices.

## How to Run
1. Open the notebook in Google Colab  
2. Run all cells sequentially  
3. Modify the ticker symbol to test different stocks  
