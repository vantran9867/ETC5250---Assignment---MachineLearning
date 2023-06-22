# ETC5250---Assignment1---MachineLearning
The ETC5250 (Machine Learning) Assignment (2023, T1) - High Distinction Grade (97%)

Restaurant Revenue Prediction

The goal of this project is to determine the important variables in modeling restaurant revenue and recommend a predictive model using R. The data used in this project is from the Kaggle competition to predict restaurant revenue.

Overview

For this assignment, the student performed a preliminary analysis of the data, identifying patterns and predicting important variables. They then split the data and fit two linear regression models - one with all variables and one with only the predicted important variables. An ANOVA was used to determine if there was a significant difference between the two models. Additional metrics such as RMSE, MAE, MAPE, and MPE were employed to evaluate the performance of the models and identify any issues.

To further investigate the important variables, the student used backward elimination with BIC and a new step-wise regression with AIC.

Next, the training data was transformed appropriately for regularization methods. The optimal tuning parameter λ was selected for lasso regression based on the average RMSE. The lambda was chosen from an appropriate range, without using the convenience function 'cv.glmnet'. The recommended model for TFI company is a lasso model with corresponding λ.

Data Sources

The data used in this project is from the Kaggle competition to predict restaurant revenue. The dataset contains information about various restaurants such as location, cuisine type, and customer ratings.

Tools Used

The project was completed using R and the following packages: dplyr, tidyverse, rsample, glmnet, yardstick, tidymodels, lubridate, stats, ggplotify, gridExtra, G.

Results

Based on the analysis performed, it was concluded that the most important variables for predicting restaurant revenue are P1, P3, and P7. The recommended model for TFI company is a lasso model with corresponding λ.
