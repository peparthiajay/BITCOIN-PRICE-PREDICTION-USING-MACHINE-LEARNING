# BITCOIN-PRICE-PREDICTION-USING-MACHINE-LEARNING
# LINEAR REGRESSION MODEL:
linear regression model predicts the future data using past data as I trained the model with past data.
model got an accuracy of 99.9%.


# ARIMA MODEL:
ARIMA(Auto Regressive Integrated Moving Average) model for prediction of BITCOIN future trends since the model uses time series data.

* *AR*: Autoregression. A Model that uses the dependent relationship between an observation and some number of lagged Observations.

* *I*: Integrated. A use of differencing of raw observations in order to make the time series stationary

* *MA*: Moving Average. A Model that uses the dependancy between an observation and a residual error from a moving average model applied to lagged Observations.

**Parameters:

* *p*: The Number of Lag Observations included in the Model, also called as Lag Order 

* *d*: The Number of times that the raw observations differenced, also called the Degree of Differencing

* *q*: The Size of the Moving Average Window, also called the Oreder of Moving Average
Structure:

*   *Yahoo Finance API*

*   Daily Prices

*   85% Data for Training and 15% Data for Testing

*   Predicting Next Day's Bitcoin Price

* my ARIMA model accuracy is 97.8%.
