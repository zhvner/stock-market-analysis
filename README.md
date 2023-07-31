## Project Description

My statistics course project aimed to develop a user-friendly platform catering to advanced 
Business Analysts who lacked programming knowledge. The primary objective was to enable 
these analysts to conduct comprehensive consultations, analyses, and modeling of stock time series data. The platform incorporated both Descriptive and Predictive analytics to facilitate specific stock searches, query particular time ranges, and perform associated analyses, such as statistical descriptions of prices and/or volume (mean, median, range, etc.). Additionally, the platform offered various technical indicators, visualizations of raw data and transformations (e.g., moving averages), and basic modeling capabilities, like regression. By leveraging these features, users could predict future prices of different companies' stocks, assisting them in making informed trading decisions within a specified period.

## System Requirements
• Windows Operating System / Mac Os
• Python 3 or higher versions
• Internet connection for real time data

## Stock Market Analysis

This repository contains a Python program for conducting a comprehensive analysis of the stock market data. The program provides both descriptive and predictive analysis of a selected company's stock.

## Prerequisites

- Python 3.0 or higher version installed on your computer (Windows/Mac).

## Installation

1. Clone this repository to your local machine using:
git clone https://github.com/your-username/stock-market-analysis.git


2. Change to the project directory:
cd stock-market-analysis


3. Install the required packages using pip:
pip3 install pandas_datareader pmdarima mpl_finance


## Usage

1. Ensure you have met the prerequisites and installed the required packages.

2. Save the `stock_market.py` program and related modules in the same folder on your computer.

3. Execute the program by opening a CMD (Windows) or Terminal (Mac) in the project directory and running the following command:

python3 stock_market.py

4. The program will prompt you to:
- Update the Nasdaq Company symbol list on your computer (optional).
- Select the company for which you want to analyze the stock by providing the company symbol as input.

5. After selecting the company, you will have the following options:
- Perform descriptive analysis: Retrieve numerical statistics and visualize historical stock data.
- Perform predictive analysis: Predict stock prices using linear regression or the ARIMA model.

## Descriptive Analysis

1. **Checking the descriptive numerical statistics:**
- Enter the "from" date and "to" date in the format of (DD/MM/YYYY) for the duration you want to retrieve numerical statistics.
- The program will provide percentage gain, mean, maximum, range, quartiles, standard deviation, and coefficient of variance for the closing share price of the selected company.

2. **Visualizing the historical stock data:**
- Enter the "from" date and "to" date in the format of (DD/MM/YYYY) for the duration you want to visualize the stock performance.
- The program will display various graphs, including candlestick graph vs. volume, close price graph, high vs. low graph, close vs. low graph, linear trendline, normalized closing price vs. volume, simple moving average, weighted moving average, Bollinger Bands, MACD, and balance of power.

## Predictive Analysis

1. **Predict stock price for the company using linear regression:**
- Enter the "from" date and "to" date in the format of (DD/MM/YYYY) for the training window.
- Enter the prediction date (past/present/future) for which you want to see the predicted price according to the linear regression model.
- The program will display the predicted price along with the R2 error value and RMS error value, along with a predicted price graph vs. actual price graph for the training window.

2. **Predict stock price using the ARIMA Model:**
- Enter the "from" date and "to" date in the format of (DD/MM/YYYY) for the training window.
- Enter the prediction date (future) for which you want to see the forecasted price according to the ARIMA model.
- The program will display the predicted price along with the RMS error value, along with a comparison of the actual price data used for testing the model within the training window vs. the predicted price for the tested price data.

## Contributing

If you find any issues or have suggestions for improvement, feel free to open an issue or create a pull request.




