# RealEstate-Price-Analysis_LinearRegression

## Model Details
This project employs a Linear Regression model to analyze and predict real estate prices based on several key features. The model is trained on historical data and aims to provide accurate predictions of house prices per unit area.

## Intended Use
The model is intended for use by real estate professionals, data analysts, and researchers interested in understanding the factors that influence real estate prices. It can be used to predict house prices, analyze market trends, and assist in decision-making processes.

## Data Source(s)
The dataset used for this project is a publicly available real estate dataset. It includes multiple features such as transaction date, house age, proximity to MRT stations, number of convenience stores, latitude, longitude, and house price per unit area.

### Repository Name
`RealEstate_Regression_Analysis`

### Dataset Sample
```
No   X1 transaction date   X2 house age   X3 distance to the nearest MRT station   X4 number of convenience stores   X5 latitude   X6 longitude   Y house price of unit area
1    2012.917              32             84.87882                                 10                                 24.98298      121.54024      37.9
2    2012.917              19.5           306.5947                                 9                                  24.98034      121.53951      42.2
```

## Training Data
The training data comprises 80% of the total dataset. It includes the features mentioned above and is used to train the Linear Regression model to learn the relationships between the features and the target variable (house price per unit area).

## Test Data
The test data comprises 20% of the total dataset. It is used to evaluate the performance of the trained model and to ensure that the model can generalize well to unseen data.

## Parameters
The Linear Regression model parameters include:
- Coefficients for each feature
- Intercept of the regression line

## Feature Importance
Feature importance is determined based on the coefficients of the Linear Regression model. Features with higher absolute coefficient values are considered more influential in predicting house prices.

## Metrics
The performance of the model is evaluated using the following metrics:
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R-squared (R²) Score

## Additional Information
This project demonstrates the application of Linear Regression in a real-world scenario. The insights gained from the model can be used to make informed decisions in the real estate market.

For further details and to view the code, visit the [GitHub repository](https://github.com/shikderraseltheprogrammer/RealEstate_Regression_Analysis).
