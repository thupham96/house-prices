# House Prices
## by Thu Pham


## Dataset

>  The Ames Housing dataset was compiled by Dean De Cock for use in data science education. It has 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. In this project, I will use feature engineering and advanced regression techniques like random forest and gradient boosting to predict house prices.

## Important Findings

- The distribution of sale price is slightly skewed to the right. The log transformation was performed to make sure the shape follows the normal distribution form. Besides, OverallQual, GrLivArea, GarageCars, GarageArea, TotalBsmtSF, 1stFlrSF, FullBath, YearRemodAdd, and YearBuilt have high correlations with SalePrice. However, there is high correlation between GarageCars and GarageArea. GarageArea was not chosen since GarageCars has higher correlation with SalePrice.
- Lasso (least absolute shrinkage and selection operator) is a regression analysis method that performs both variable selection and regularization in order to enhance the prediction accuracy and interpretability of the resulting statistical model. The Lasso model in this project returns the root mean squared error of 0.14014.
- Random Forest Regression is a supervised learning algorithm that uses ensemble learning method for regression. Ensemble learning method is a technique that combines predictions from multiple machine learning algorithms to make a more accurate prediction than a single model. The Random Forest Regression model in this project returns the root mean squared error of 0.15329.
- Gradient Boosting is a type of machine learning boosting. It relies on the intuition that the best possible next model, when combined with previous models, minimizes the overall prediction error. The Gradient Boosting model in this project returns the root mean squared error of 0.14377.


## Credits

Kaggle (https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
