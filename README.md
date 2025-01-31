# Spark Regression Modales for Power Plant
## Requirements:
###### 1.Google Colab
###### 2.SparkSession
###### 3.LinearRegression
###### 4.VectorAssembler
###### 5.DecisionTreeRegressor
###### 6.RegressionEvaluator
###### 7.GBTRegressor
This project implements different regression models using Apache Spark (PySpark) to predict the energy output of a power plant based on environmental and operational features.

## Dataset
The dataset contains sensor readings from a power plant, including:

AT: Ambient Temperature
V: Exhaust Vacuum
AP: Ambient Pressure
RH: Relative Humidity
PE: Net hourly electrical energy output (Target variable)

## Model Used
The following regression models were implemented and compared:

1. Linear Regression
2. Decision Tree Regressor
3. Gradient Boosted Trees (GBT) Regressor
## Results (RMSE Comparison)
Linear Regression: 4.56
Decision Tree Regressor: 4.49
Gradient Boosted Trees (GBT) Regressor: 4.00 (Best Model)

## Author
👤 Mohammadreza Tabatabaei
📧 Tabatabaei.mhr@gmail.com
