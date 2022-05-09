# Profit Forecasting for Super Stores

This repository contains a machine learning project for profit forecasting. 
The forecasting is done on a dataset from Kaggle which contains sales data of an american super store for office supplies. 
We use machine learning algorithms to predict the profit of a sold product in this dataset. 

The project is divided in four notebooks, which are explained in the following sections. 

## Data_Understanding
This notebook gives an insight of the used dataset. Visualizations of the data are provided.

## Profit_Forecasting
This is the main notebook which implement the ML pipeline. Following steps are implemented:
1) Data Preparation with feature engineering and scaling of the data 
2) Modelling phase with algorithm selection and training phase
3) Evaluation of the trained models on test data

## Profit_Forecasting_Neural_Network 
In this notebook, a neural network is implemented. Because of the more complex architecture of this algorithm, it is implemented in an own pipeline. 
Nonetheless, the data preparation is done in the same way as in the main pipeline. 


## Hyperparameter_Optimization
This notebook contains the implementation of sklearn's hyperopt package for hyperparameter tuning. It tunes the parameters of the XGBoost, Gradient Boosting, Decision Tree Regressor and linear regression. 




