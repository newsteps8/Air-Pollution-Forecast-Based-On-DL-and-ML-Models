# Air-Pollution-Forecast-Based-On-DL-and-ML-Models
This repository has been created for air pollution forecast in the coming hours in Beijing.


**Comments**

Root Mean Square Error of Random Forest Regressor: 74.45430231198172 | Root Mean Square Error of XGBOOST Regressor: 65.8382656621441 | Root Mean Square Error of LSTM Sequential Model: 23.484

Best model is LSTM model. Because I convert the dataset to time series version based on multivarible and use a Sequential model on it. XGBOOST and Random Forest Regressor models errors must be less than above values. One of the reasons is XGBOOST is a Gradient boosting algorithm. So, Gradient boosting can be used to minimize any sensible loss function, and it is very effective in doing it. In addition, for XGBOOST and Random Forest Regressor models with hyperparemeter tuning, parameter values can be improved and better results can be obtained.

Also lstm model can be improved based on optimizer, more epochs and decreasing loss value of each iteration. I think RMSE value can be decreased around 10.0 - 20.0 values with the help of optimizations and better models.
