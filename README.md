# U.S. Automotive Price Prediction: Multiple Linear Regression

## Project Overview
This project analyzes key factors influencing U.S. car prices to assist Geely Auto, a Chinese automobile company, in expanding into the U.S. market. Using a dataset from Kaggle, we apply multiple regression techniques to predict car prices based on various features like engine size, horsepower, and fuel efficiency.

## Dataset
- Source: [Car Price Prediction Dataset from Kaggle](https://www.kaggle.com/datasets/hellbuoy/car-price-prediction)
- **Observations:** 206
- **Features:** 25 predictors including car attributes such as engine size, horsepower, and fuel efficiency.

## Methodology
We implemented three modeling strategies to predict car prices:
1. **Multiple Linear Regression (MLR):** 
   - Explains relationships between car price and independent variables.
   - Adjusted R-squared: 0.884.

2. **Lasso Regression:**
   - Introduces L1 regularization to perform feature selection.
   - Mean Squared Error: $3,448,576.61.

3. **Ridge Regression:**
   - Employs L2 regularization to reduce multicollinearity without feature elimination.
   - Mean Squared Error: $3,060,834.67.

## Key Insights
- Significant variables include engine size, horsepower, fuel system, and cylinder number.
- The Ridge regression model explained 93% of the variance in car prices, outperforming both MLR and Lasso.

## Additional Resources
For detailed analysis, including data transformations, EDA, and model results, refer to the full project report
---
