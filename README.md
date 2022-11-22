# Time Series analysis on Historical Data and Google Trends

This project is to compare Autoregressive Integrated Moving Average (ARIMA) and Long Short-Term Memory (LSTM) models for various time series data. I created generalized functions that could quickly test, iterate, and optimize ARIMA and LSTM models for a given time series input. The general models were used to forecast various trends, including:
- NIFTY 50 historical data
- S&P 500 historical data
- "Coldbrew" Google Trends
- "Olympics" Google Trends
- "Zika Virus" Google Trends

I chose these various trends based on their unique shapes to test a variety of seasonality changes, increasing values over time, and sharp disparities. Each section contains a plot of the original data, followed by out-of-sample testing results. 

Further, I included results that used gaussian filtering to smooth the original dataset, followed by modeling of the smoothed dataset. The smoothed modeling results were compared to the original series data to determine whether the filtering improved performance of the models.

### Key Questions Explore
Given a wide range of time series data sets,
- Which model performed better at prediction out-of-sample data: ARIMA or LSTM?
- Does gaussian filtering improve the model results on the original, un-filtered dataset? 

### Techniques used
- time series analysis and forecasting
- pandas and numpy for datetime, data preparation
- statsmodel and keras for ARIMA and LSTM modeling
