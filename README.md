# Timeseries_Quarterly-Coal-Power-Analysis
A comprehensive analysis using AR, MA, ARMA, and ARIMA models for quarterly coal power consumption forecasting. This work delves into data preprocessing, stationarity testing, trend and seasonality analysis, and predictive modeling to aid energy sector decision-making and policy formulation.

## Project Aim

This project aims to analyze the seasonality and trends in quarterly coal power consumption using time series analysis. Through the application of statistical tests and predictive modeling, including AR, MA, ARMA, and ARIMA, we seek to forecast future coal power usage to inform energy policy and planning decisions.

## Key Results

- **Stationarity Achieved**: The Augmented Dickey-Fuller (ADF) test on the differenced data confirmed the series became stationary, with a test statistic of -4.510983475470282, significantly lower than the critical values at 1%, 5%, and 10% levels. This indicates strong evidence against the null hypothesis of a unit root, confirming the effectiveness of differencing in achieving stationarity.

- **Stationarity Challenges with Moving Averages**: Initial attempts using moving averages did not result in a stationary series, underscoring the complexity of the underlying data and the need for more sophisticated differencing and modeling approaches.

- **Model Selection and Forecasting**: The subsequent application of ARIMA modeling, informed by the ACF and PACF plots, allowed for the development of a predictive model that takes into account the seasonal patterns identified in the quarterly data.

The project's findings underscore the importance of thorough data preprocessing and the strategic use of statistical tests to guide the selection of appropriate time series models. The successful forecasting of coal power consumption can significantly aid in the development of more resilient and informed energy policies.
