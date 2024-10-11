# Stock Price Prediction for Time-Series Data.

## Data Preprocessing:
Loaded stock price data, renamed columns for simplicity.
Converted "Volume" and "Change %" to numeric data types.
Converted "Date" to datetime format for time-based analysis.

## Exploratory Data Analysis (EDA):
Visualized stock price trends, volume, and percentage change over time.
Analyzed the distribution of percentage change, revealing market stability.
Calculated 20-day and 252-day moving averages and volatility to observe trends.

## Correlation Analysis:
Created a correlation matrix, showing strong relationships between stock prices (Open, Close, High, Low).
Weak negative correlation between stock prices and trading volume.

## Outlier Detection:
Used Z-scores to identify outliers in price and volume.
Visualized these outliers to highlight significant price or volume deviations.

## Anomaly Detection:
Identified anomalies using rolling means and standard deviations (2 std deviation threshold).
Highlighted potential market shocks or events affecting stock prices.

## Stationarity Testing:
Performed the Augmented Dickey-Fuller test to check for non-stationarity, confirming that the time series is non-stationary.

## Trend Analysis:
Visualized long-term (Monthly) vs short-term (Weekly) moving averages, showing overall price stability.
Applied seasonal decomposition to capture trend, seasonality, and residuals in stock prices.

## Standardization:
Standardized all numerical columns to normalize data for further analysis or modeling.

## RSI and MACD:
Calculated Relative Strength Index (RSI) to identify overbought/oversold conditions.
Set up Moving Average Convergence Divergence (MACD) analysis for identifying potential bullish or bearish trends.

## Modelling
We used 4 models in this project for prediction
Support Vector Machine
XGBoost
LSTM ( Long Short term Memory )
ARIMA ( AutoRegressive Integrated Moving Average )

## Evaluation 
We have evaluated each model using metrics like
MSE: Mean Sqaured Error
MAE: Mean Absolute Error
MAPE: Mean Absolute percentage Error
R-Squared: R2 error score

