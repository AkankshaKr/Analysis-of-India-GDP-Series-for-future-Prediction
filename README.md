# Analysis-of-India-GDP-Series-for-future-Prediction
In this project, We analyzed India's GDP series over several years that is 1973 to 2022, using historical data to predict future trends. The analysis involved:

Data Cleaning and Visualization: started by loading and cleaning the dataset, plotting GDP trends over time to visually assess how the GDP values have changed. This provided a clear picture of any secular trends or long-term movements in the GDP.

Time Series Analysis: You checked for seasonality, cycles, and secular trends within the dataset. Our analysis revealed a significant secular trend, indicating a consistent upward movement in India's GDP over the period of analysis.

ARIMA Model for Forecasting: Given that the GDP series was non-stationary, applied the ARIMA (AutoRegressive Integrated Moving Average) model to forecast future GDP values. This model is particularly useful for capturing both the autoregressive and moving average components of the time series. We used the auto.arima function to automate the selection of p, d, and q parameters, and analyzed ACF and PACF plots to validate the model fit. ACF (Autocorrelation Function) and PACF (Partial Autocorrelation Function) are both tools used in time series analysis to help identify the appropriate model for forecasting, particularly for ARIMA models.

Results and Forecasting: The ARIMA model successfully predicted India's GDP for 2023 and 2024, with results indicating a predicted GDP of approximately 3074 billion USD in 2023 and 3193 billion USD in 2024 (constant 2015 dollars). These forecasts were visualized to highlight potential future trends in India's economy.
