# Grab-AI-for-SEA---Traffic-Management-Challenge

The goal of the challenge was to forecast the Grab riding demand over the 1329 geohash coordinates in 15-min time frame.
 
Conducted data exploration and visualization, results show that there are peak hour for the demand, coordinate with highest demand and different demand between the particular day.
 
Applied PCA transformation to reduce the dimension to 1D to treat it as univariate time series to experimentally process with ARIMA, SARIMAX and LSTM model and compare with VAR & VARMA multivariate time series modelling results.
 
The best model was VAR model incorporate with PCA retained 95% variations throughout my experiments and achieved RMSE: 0.0418 over 672 test samples.
