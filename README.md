# Stock_market_prediction
## Overview
This project aims to predict stock market prices using machine learning techniques. The code provided in this repository demonstrates a simple example of stock market prediction using linear regression.

## Data
The project uses two CSV files named 'df_msft.csv' and 'df_reliance.csv'. Each file contains historical stock market data for a specific company (Microsoft and Reliance Industries, respectively) with the following columns:
- Date: The date of the stock data.
- Open: The opening price of the stock on that date.
- High: The highest price of the stock during the trading day.
- Low: The lowest price of the stock during the trading day.
- Close: The closing price of the stock on that date.
- Adj Close: The adjusted closing price, which accounts for stock splits and dividends.
- Volume: The trading volume of the stock on that date.

## Getting Started
1. Clone this repository to your local machine.
2. Ensure you have Python (version 3.6 or higher) installed on your system.
3. Install the required Python packages listed in 'requirements.txt'.

## Code Structure

The main Python script for stock market prediction is 'stock_market_prediction.py'. The script follows these steps:
1. Load and preprocess the data from the CSV files.
2. Handle any missing values in the data.
3. Concatenate the data from both companies and create a target variable for prediction ('Next_Close').
4. Split the data into training and testing sets.
5. Train a Linear Regression model on the training data.
6. Evaluate the model's performance on the test set using Mean Squared Error (MSE).
7. Perform cross-validation to get a more robust estimate of the model's performance.
8. Provide an example of predicting the next day's close price for new data.

The code will print the Mean Squared Error (MSE) for the test set and the mean MSE with cross-validation. Additionally, it will show the predicted close price for a new data point.

## Disclaimer

Stock market prediction is a complex and uncertain task. The predictions made by the models are not guaranteed to be accurate or reliable. This project is intended for educational and demonstration purposes only and should not be used as financial advice. Always consult with financial professionals and conduct thorough research before making any investment decisions.


