# Predicting the number of taxi orders for the next hour
The project from the Time Series sprint of the Practicum DS course.

## Description
Here we have a dataset on taxi orders at airports. Our goal is to build a model for predicting the number of taxi orders for the next hour.

First, we should do some data preprocessing: clean the data, fill in the missing values (if any), and change data types. Next, we need to scale and encode the data. Afterward, we could proceed to model development.

## Conclusion
After preprocessing, we explored several models using the RMSE score and GridSearchCV to look for the best hyperparameters. Our best model was the CatBoost Regressor.