# evaluation-of-predictive-models-in-the-field-of-data-science
The evaluation of predictive models in the field of data science
# Project Introduction

Welcome to our data science project repository, where we explore the evaluation of predictive models in the field of data science. In this project, we focus on assessing the accuracy and reliability of various models using the Mean Absolute Error (MAE) and Symmetric Mean Absolute Percentage Error (sMAPE) metrics.

## Model Evaluation with MAE

In predictive modeling, model accuracy is crucial, and we use the Mean Absolute Error (MAE) to measure how well our models align with true values. An MAE value close to zero indicates high accuracy, suggesting that the model's predictions closely match the actual data. In this project, we obtained an MAE value of 7.883623897364653e-15, indicating an extremely small average difference between predicted and actual values. However, it's important to consider the context and details of the model and calculations to fully understand this result.

## Concentration Analysis

Our project also involves an analysis of the concentration of gold (Au), silver (Ag), and lead (Pb) throughout a purification stage. Gold concentration shows a linear increase, while silver fluctuates but generally decreases, and lead concentration slightly increases. This analysis provides insights into the chemical properties of these elements during the purification process.

## sMAPE Calculation

We have developed a function to calculate the final sMAPE value for our models. The steps involved in this process include data preprocessing, training and fitting models using DecisionTreeRegressor, RandomForestRegressor, LinearRegression, and a final model using RandomForestRegressor with 40 n_estimators. We also considered a constant model predicting the mean.

## Conclusion

The best-performing model in our analysis is the RandomForestRegressor with 40 n_estimators, achieving an sMAPE of 8%. Surprisingly, the constant model predicting the mean performs similarly with an sMAPE of 7.6%. This suggests that our machine learning models do not significantly outperform a simple mean-based model.

The Linear Regression model also performs reasonably well, with a mean sMAPE of 0.07215046419932944, similar to the best model. The Decision Tree Regressor outperforms both the Linear Regression model and the best model, with a lower mean sMAPE of 0.05716637539353366, indicating improved predictive performance.

In conclusion, the Decision Tree Regressor appears to be the most suitable model for our task due to its superior predictive performance. However, further analysis and evaluation are necessary to validate its reliability and generalizability. We recommend considering additional evaluation metrics and comparing the DTR model with alternative models to make an informed choice for your specific problem.
