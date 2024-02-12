# Timeseries_Quarterly-Coal-Power-Analysis
A comprehensive analysis using AR, MA, ARMA, and ARIMA models for quarterly coal power consumption forecasting. This work delves into data preprocessing, stationarity testing, trend and seasonality analysis, and predictive modeling to aid energy sector decision-making and policy formulation.

## Project Aim

This project aims to analyze the seasonality and trends in quarterly coal power consumption using time series analysis. Through the application of statistical tests and predictive modeling, including AR, MA, ARMA, and ARIMA, we seek to forecast future coal power usage to inform energy policy and planning decisions.

## Key Steps

1. **Data Preprocessing**: Initial steps included cleaning and transforming the coal power consumption data into a format suitable for time series analysis.

2. **Exploratory Data Analysis (EDA)**: Visual examination of the data was conducted to identify trends, seasonal patterns, and any anomalies.

3. **Stationarity Testing**: The Augmented Dickey-Fuller (ADF) test was applied to assess the stationarity of the series, a critical prerequisite for ARIMA modeling.

4. **Seasonality and Trend Decomposition**: The data was decomposed to separate the trend and seasonal components, providing insights into the underlying patterns.

5. **Autocorrelation Analysis**: ACF and PACF plots were generated to guide the selection of appropriate ARIMA model parameters by identifying significant lags.

6. **Model Fitting and Evaluation**: Various time series models (AR, MA, ARMA, ARIMA) were fitted to the data, with their performance evaluated based on their ability to capture the data's dynamics.

## Key Results

- **Stationarity Achieved**: The Augmented Dickey-Fuller (ADF) test on the differenced data confirmed the series became stationary, with a test statistic of -4.510983475470282, significantly lower than the critical values at 1%, 5%, and 10% levels. This indicates strong evidence against the null hypothesis of a unit root, confirming the effectiveness of differencing in achieving stationarity.

- **Stationarity Challenges with Moving Averages**: Initial attempts using moving averages did not result in a stationary series, underscoring the complexity of the underlying data and the need for more sophisticated differencing and modeling approaches.

- **Model Selection and Forecasting**: The subsequent application of ARIMA modeling, informed by the ACF and PACF plots, allowed for the development of a predictive model that takes into account the seasonal patterns identified in the quarterly data.

The project's findings underscore the importance of thorough data preprocessing and the strategic use of statistical tests to guide the selection of appropriate time series models. The successful forecasting of coal power consumption can significantly aid in the development of more resilient and informed energy policies.
