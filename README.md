# Fintech-TimeSeries

# Unit 10—A Yen for the Future

![Yen Photo](Images/yen.jpg)

## Background

This repository inludes a time series analysi and regression_analysis of the Canadian Dollar and Yen exchange rates.

### Files

[Time-Series Starter Notebook](Code/time_series_analysis.ipynb)

[Linear Regression Starter Notebook](Code/regression_analysis.ipynb)

[CAD/JPY Data CSV File](Code/cad_jpy.csv)

- - -

# Overview/Analysis

## 1. Decreasing Canadian Strength

The analysis showed that the Canadian dollar could purchase less and less Yen over time. This indicates that the Japanese economy has strengthened in the last 20 years compared to the Canadian dollar, causing a better exchange rate for the Yen.

![The-Yen-Comback](Images/devaluing_CAD.png)

Furthermore, the price noise calculation shows high volatility in the exchange rate with a few periods of extremely high volatility due to global crises, indicating instability in price action.

![Price Volatility](Images/CAD-PHY_price_noise.png)


## 2. What does the Future Hold?

Forcasting returns using the ARMA model shows us the predicted returns based off past returns. As we can see the Canadian dollar has been steadily purchasing less YEN per its dollar and thus the returns y value is negative.

![ARMA Model Results](Images/ARMA_forcast_summary.png)

![Price Volatility](Images/ARMA_forcast_plot.png)

Furthermore, the ARIMA model shows us a descending price value, highlighting a continued drop in value of the Canadian dollar compared to the Yen.

![ARMA Model Results](Images/ARIMA_forcast_summary.png)

![Price Volatility](Images/ARIMA_forcast_plot.png)


## 3. Decisions, Decisions, Decisions

## 4. The Final Frontier


#### Linear Regression Forecasting

In this notebook, you will build a Scikit-Learn linear regression model to predict CAD/JPY returns with *lagged* CAD/JPY futures returns and categorical calendar seasonal effects (e.g., day-of-week or week-of-year seasonal effects).

Follow the steps outlined in the regression_analysis starter notebook to complete the following:

1. Data preparation (creating returns and lagged returns, and splitting the data into training and testing data)
2. Fitting a linear regression model.
3. Making predictions using the testing data.
4. Out-of-sample performance.
5. In-sample performance.

Use the results of the linear regression analysis and modelling to answer the following question:

* Does this model perform better or worse on out-of-sample data compared to in-sample data?

- - -


