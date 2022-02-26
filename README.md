# StocksApp
A ML computer app that predicts stocks for day trading.

This app is essentially a machine learning model that takes data from different S&P 500 stocks as an input, and produces the predicted change in price of the stock as an output. To do this I will draw historical data from an API, and use this data to train 

The idea is see if it's possible to predict a stock's high for the next day, buy a stock near closing time (around 4:15pm), and sell the stock the next day when it's above yesterday's buying price.
