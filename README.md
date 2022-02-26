# Regression Housing Price Prediction
This project explored the following regression methods to predict housing prices in King County
1. Ordinary Least Squares
2. Lasso
3. Ridge
4. Decision Tree Regression
5. Elastic Net
6. Support Vector Regression
7. K Nearest Neighbours Regression
8. XGBoost

The models were evaluated using **Root Mean Square Error (RMSE)** and **residual analyses**.

The best approach with the lowest prediction error was to generate two XGBoost models for different regions: (1) downtown and (2) non-downtown, using the same features but with different weights. The residuals show some deviance from normality, but not too serious.

Read the project's story in the [summary slides](https://github.com/Shu-x/Regression_Housing_Price_Prediction/blob/main/Summary.pdf).
