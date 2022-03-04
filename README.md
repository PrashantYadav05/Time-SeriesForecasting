# Time-Series Forecasting
## Load & explore Time-Series data: 
(header=0: We must specify the header information at row 0, parse_dates=True: We give the function a hint that data in the first column contains
dates that need to be parsed, index col=0: We hint that the first column contains the index information for the timeseries, squeeze=True: We hint that we only have one data column and that we are interested in a Series and not a DataFrame)
* How to load your time series dataset from a CSV file using Pandas.
* How to peek at the loaded data and query using date-times.
* How to calculate and review summary statistics.

## Basic Feature Engineering:
* Date Time Features
*  ![alt text](time-features.webp)
* Lag Features (shift())
* Rolling Window Statistics (rollling(window=2)
* Expanding Window Statistics

## Data visualization:
* Line Plots (pd.grouper())
* Histograms and Density Plots.
* Box and Whisker Plots.
* Heat Maps.
* Lag Plots or Scatter Plots.
* Autocorrelation Plots.
## Resampling & Interpolation:
resample('D') to resample & interpolate() function to interpolate missing values.
## Power transforms:
* Identify a quadratic change and use the square root transform.
* Identify an exponential change and how to use the log transform.
* Use the Box-Cox transform to perform square root and log transforms andautomatically optimize the transform for a dataset.
## Moving Average Smoothing
## Introduction to White Noise
A time series is white noise if the variables are independent and identically distributed with a mean of zero. This means that all variables have the same variance (sigma2) and each value has a zero correlation with all other values in the series.
* White noise time series is defined by a zero mean, constant variance, and zero correlation, 
* If your time series is white noise, it cannot be predicted, and if your forecast residuals are not white noise, you may be able to improve your model.
## Introduction to the Random Walk
* Random Walk and Autocorrelation.
* Random Walk and Stationarity.
## Decompose Time Series Data: 
* y(t) = Level + Trend + Seasonality + Noise, y(t) = Level * Trend * Seasonality * Noise
## Use and Remove Trends
* The importance and types of trends that may exist in time series and how to identify them.
* How to use a simple differencing method to remove a trend.
* How to model a linear trend and remove it from a sales time series dataset.
## Use and Remove Seasonality
## Stationarity in Time Series Data
## Backtest Forecast Models
## Forecasting Performance Measures
## Persistence Model for Forecasting
## Visualize Residual Forecast Errors
## Reframe Time Series Forecasting Problems
## Introduction to the Box-Jenkins Method
## Autoregression Models for Forecasting
## Moving Average Models for Forecasting
## ARIMA Model for Forecasting
## Autocorrelation and Partial Autocorrelation
## Grid Search ARIMA Model Hyperparameters
## Forecast Confidence Intervals

## Prepare "Time Series" data for CNNs and LSTMs:
## Develop CNNs for Time SeriesForecasting:
