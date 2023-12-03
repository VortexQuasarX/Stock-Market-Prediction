# Stock Market Analysis and Prediction using LSTM

## Project Overview

The project aims to conduct a thorough analysis of stock market data, with a focus on technology stocks, including Apple (AAPL), Amazon (AMZN), Google (GOOG), and Microsoft (MSFT). The analysis covers various aspects, such as visualizations of stock prices, daily returns, moving averages, correlation between stocks, risk assessment, and the development of a predictive model using Long Short-Term Memory (LSTM) neural networks.

## Table of Contents

- [Data Retrieval and Exploration](#data-retrieval-and-exploration)
- [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)
    - [Visualizing Stock Prices Over Time](#visualizing-stock-prices-over-time)
    - [Moving Averages](#moving-averages)
    - [Daily Returns](#daily-returns)
    - [Correlation Analysis](#correlation-analysis)
    - [Risk Assessment](#risk-assessment)
- [LSTM Model for Stock Price Prediction](#lstm-model-for-stock-price-prediction)
- [Results and Visualizations](#results-and-visualizations)
- [Conclusion and Future Work](#conclusion-and-future-work)
- [Acknowledgments](#acknowledgments)
- [Questions and Contributions](#questions-and-contributions)
- [License](#license)

## Data Retrieval and Exploration

- The data was obtained from Yahoo Finance using the `yfinance` library.
- Initial exploration involved checking the structure of the data, identifying missing values, and gaining insights into the available features.

## Exploratory Data Analysis (EDA)

### Visualizing Stock Prices Over Time

- The historical closing prices of each stock were visualized over time.
- Insights were gained into the overall trends and fluctuations in stock prices.

### Moving Averages

- Moving averages (10, 20, and 50 days) were calculated and plotted to identify trends and smooth out price data.

### Daily Returns

- Daily returns were analyzed to understand the percentage change in stock prices on a daily basis.
- Histograms and KDE plots were used to visualize the distribution of daily returns.

### Correlation Analysis

- The correlation between different stocks was examined using scatter plots, pair plots, and correlation matrices.
- Insights were gained into how stocks move in relation to each other.

### Risk Assessment

- The relationship between expected return and risk (standard deviation of daily returns) was visualized.
- A scatter plot highlighted the risk-return profile of each stock.

## LSTM Model for Stock Price Prediction

- A predictive model using Long Short-Term Memory (LSTM) neural networks was developed to forecast the closing price of Apple Inc.
- The data was preprocessed, including scaling using MinMaxScaler.
- The LSTM model architecture was defined, compiled, and trained on the training data.
- The model was evaluated on the test data, and predictions were inverse-transformed for comparison with actual stock prices.
- The Root Mean Squared Error (RMSE) was calculated to assess the model's performance.

## Results and Visualizations

- The project's findings were summarized, and key visualizations were presented in the README.
- Visualizations included stock price trends, moving averages, daily returns, correlation matrices, and the LSTM model's predictions.

## Conclusion and Future Work

This project provides valuable insights into the behavior of technology stocks and offers a predictive model for stock price forecasting. Future work could involve refining the predictive model, exploring additional features, and expanding the analysis to include more stocks or economic indicators.

## Acknowledgments

- The project is inspired by the [Learning Python for Data Analysis and Visualization](https://www.udemy.com/course/learning-python-for-data-analysis-and-visualization/) Udemy course by Jose Portilla.
- Special thanks to the [yfinance](https://pypi.org/project/yfinance/) library for providing access to Yahoo Finance data.

## Questions and Contributions

- Questions and contributions are welcome! Feel free to open issues or submit pull requests on the GitHub repository.

