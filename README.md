# Time-Series Forecasting
## Load & explore Time-Series data: 
(header=0: We must specify the header information at row 0, parse dates=True: We give the function a hint that data in the rst column contains
dates that need to be parsed, index col=0: We hint that the first column contains the index information for the time
series, squeeze=True: We hint that we only have one data column and that we are interested in a Series and not a DataFrame)
* How to load your time series dataset from a CSV file using Pandas.
* How to peek at the loaded data and query using date-times.
* How to calculate and review summary statistics.

## Basic Feature Engineering:
* Date Time Features
* Lag Features
* Rolling Window Statistics
* Expanding Window Statistics

## Data visualization:
* Line Plots.
* Histograms and Density Plots.
* Box and Whisker Plots.
* Heat Maps.
* Lag Plots or Scatter Plots.
* Autocorrelation Plots.
## Resampling & Interpolation:
## Power transforms:
## Moving Average Smoothing
## Introduction to White Noise
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

