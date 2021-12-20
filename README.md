# Sales-prediction
Using a time series data for the prediction of sales  
When we make a model for forecasting purposes in time series analysis, we require a stationary time series for better prediction.
So we use Augmented Dickey-Fuller test for checking whether our time series data is stationary or not.
After performing adfuller test we got know that the data is not stationary.
So we perform several steps like apply log, squaring, Exponentially Weighing Averages(EWA), Scaling etc., kind of steps to make data stationary.
After attaining stationary in data we use Auto Correlation Function(ACF) and Partial Auto Correlation Function(PACF) for getting to know what kind of ARIMA model we should use.
As a final using the proper ARIMA model and fitting the data in that model.
