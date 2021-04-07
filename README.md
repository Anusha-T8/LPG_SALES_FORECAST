The data used for this project includes quarterly sales of Liquified Pertroleum gas in tonnes value. 

The model driven methods are performed to find the best fit for prediction. The model with least RMSE value is choosen to be good fit

I have used the method of rolling mean and rolling standard deviation to achieve stationarity and statsmodel.seasonal_decompose for decomposing the seasonality. Later ARIMA is performed on the stationary data to forecast at 95% confidence interval.
