# Predict-Future-Stock-Prices

# Next-Day Closing Price

## Objective
Predict the next day's closing price of a stock using historical data. This project uses features like Open, High, Low, and Volume to train a regression model.

## Dataset
Historical stock market data is retrieved from **Yahoo Finance** using the `yfinance` Python library.

## Features Used
- Open: Opening price of the stock
- High: Highest price of the stock during the day
- Low: Lowest price of the stock during the day
- Volume: Number of shares traded
- Target: Next day's Close price

## Model
- **Linear Regression** is used to predict the next day’s closing price.
- Optional: Random Forest Regression can also be used for potentially better performance.

## Instructions
1. Install required libraries: `yfinance`, `pandas`, `numpy`, `matplotlib`, `scikit-learn`
2. Download historical stock data using `yfinance.download()`
3. Preprocess data to create features and the next-day target
4. Train the model on historical data
5. Evaluate using MAE and RMSE
6. Plot actual vs predicted closing prices

## Visualization
The project includes a plot comparing actual vs predicted closing prices for easy performance evaluation.

## Example Stock
- Apple (AAPL) is used as an example in the code. You can change the symbol to any other stock like Tesla (TSLA), Microsoft (MSFT), etc.

## Author
- Manaseh Shamim
