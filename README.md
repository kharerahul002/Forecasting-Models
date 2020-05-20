# Forecasting-Models

Forecasting is the process of making predictions of the future based on past and present data and most commonly by analysis of trends. A commonplace example might be estimation of some variable of interest at some specified future date. Prediction is a similar, but more general term.


# List of Models We tried 

1. ARIMA : 

ARIMA models are among the most widely used approaches for time series forecasting. The name is an acronym for AutoRegressive Integrated Moving Average.
In an AutoRegressive model the forecasts correspond to a linear combination of past values of the variable. In a Moving Average model the forecasts correspond to a linear combination of past forecast errors.
Basically, the ARIMA models combine these two approaches. Since they require the time series to be stationary, differencing (Integrating) the time series may be a necessary step, i.e. considering the time series of the differences instead of the original one.


2. SARIMAX:

The implementation is called SARIMAX instead of SARIMA because the “X” addition to the method name means that the implementation also supports exogenous variables. ... Exogenous variables are optional can be specified via the “exog” argument.
The SARIMA model (Seasonal ARIMA) extends the ARIMA by adding a linear combination of seasonal past values and/or forecast errors.


3. Autoregressive:

An autoregressive model is when a value from a time series is regressed on previous values from that same time series. ... The order of an autoregression is the number of immediately preceding values in the series that are used to predict the value at the present time.


4. Moving Average:

In time series analysis, the moving-average model, also known as moving-average process, is a common approach for modeling univariate time series. Rather than using past values of the forecast variable in a regression, a moving average model uses past forecast errors in a regression-like model.


5. RNN-LSTM:

LSTM models can be used to forecast time series (as well as other Recurrent Neural Networks). LSTM is an acronym that stands for Long-Short Term Memories.
The state of a LSTM network is represented through a state space vector. This technique allows to keep tracks of dependencies of new observations with past ones (even very far ones).


6. FB-Prophet:

Prophet is another forecasting model which allows to deal with multiple seasonalities. It is an open source software released by Facebook’s Core Data Science team.
There are two options for trend time series: a saturating growth model, and a piecewise linear model. The multi-period seasonality model relies on Fourier series.


7. Decison Tree:

Decision Trees are probably one of the most useful supervised learning, in supervised learning your existing data is already labelled and you know which behaviour you want to predict in the new data you obtain. 
It uses algorithms that progressively divide data sets into smaller data groups based on a descriptive feature, until they reach sets that are small enough to be described by some label.


8. Linear Regression:

linear regression models are models that have a certain fixed number of parameters that depend on the number of input features, and they output a numeric prediction, like for example the price of a stock.


9. Support Vector Machine(Regression):

Support vector machines so called as SVM which can be used for classification and regression problems as support vector classification (SVC) and support vector regression (SVR).
SVM is based on the idea of finding a hyperplane that best separates the features into different domains.


# How to choose best Models and Which are those Models

As we build the model, we also calculate the RMSE (Root Mean Squered Error) and Acuuracy of the Model. 
Check for the each model which giving us the best accuracy and least error i.e lowest RMSE (between 0.2 -0.5 is the best) and models that give us a best prediction result, we opt that model.

In Above Models we tried to do forecasting using Stock Market Data from Quandl Website which contains all historical data.
As we already done with our model now the time is to select best predictive model(only for Quandl Data)

Models which are given best results are as follows:

1. RNN-LSTM
2. ARIMA
3. SARIMAX
4. FB-Prophet


