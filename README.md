# OLS-Regression-Strategy
Introduction<br>
ordinary least squares (OLS) is a type of linear least squares method for choosing the unknown parameters in a linear regression model by the principle of least squares: minimizing the sum of the squares of the differences between the observed dependent variable in the input dataset and the output of the (linear) function of the independent variable.

Methodology<br>
For backtesting the strategy, I have used Python with Pandas,Numpy,Matplot and QuantStats libraries.
The strategy used is using historical returns to estimate the direction of the next days market movement.

Backtest<br>
For the backtesting data I have used daily data of EUR over the past 10 years starting from 01-11-2013.
The strategy uses a lag of 7 return of days to estimate the direction of the next days price movement.

