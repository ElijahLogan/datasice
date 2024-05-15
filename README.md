Mean Absolute Error (MAE): This is the average of the absolute differences between predictions and actual values. It provides an idea of how wrong the predictions were. A smaller value indicates a better model fitness. Example: MAE = 3.5 can be interpreted as "on average, our predictions are 3.5 units away from the actual values".

Mean Squared Error (MSE): This is the average of the squared differences between predictions and the actual values. The squaring is done to penalize even a small error, which can result in making a bigger impact. Therefore, a smaller MSE means a better model. Example: MSE = 4 can be interpreted as "on average, the squares of the differences between our predictions and the actual values are 4".

Root Mean Squared Error (RMSE): This is the square root of the MSE. It is also a measure of the differences between predicted and actual values. RMSE also punishes large errors and is differentiable, which makes it easier to perform optimization tasks. Example: RMSE = 5 can be interpreted as "our model's predictions are, on average, 5 units away from the actual values".

R Squared (R^2): This depicts the proportion of the variance in the dependent variable that is predictable from the independent variable(s). The closer R^2 is to 1.0, the better the model explains the variability in the input data. Example: R^2 = 0.8 can be interpreted as "our model explains 80% of the variation in the data".

Adjusted R Squared (Adj R^2): This adjusts the R^2 for having too many input variables and besides that works similar to R^2. When comparing two models, the one with higher Adj R^2 is a better model. Example: Adj R^2 = 0.76 can be interpreted as "after adjusting for the number of predictors, our model explains 76% of the variation in the data".

In summary, all these metrics contribute to a holistic understanding of how well your model fits the data. Lower error rates (MAE, MSE, RMSE) and higher explanatory power (R^2, adjusted R^2) are desirable in a well-fitted model.
