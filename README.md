# House_Price_Prediction_with_Pyspark
Predicting House Prices using Linear Regression, Random Forest and GBT Regression in with Pyspark
## Objective

The objective of this data science project is to develop a machine learning model that can accurately predict the prices of residential houses based on various features such as location, size, number of bedrooms and bathrooms, and other relevant factors. The ultimate goal of the project is to create a predictive model that can be used to assist real estate agents, property investors, and prospective home buyers in making informed decisions about buying and selling residential properties.
## Requirements

- Ames Housing Dataset
- Root Mean Squared Error (RMSE)
- R-Squared value
- Mean Percentage Difference

## Algorithm

We used machine learning techniques, such as linear regression, random forests, and gradient boosted trees to predict the sale price of a house based on its features. We used Root Mean Squared Error (RMSE), R-Squared value, and Mean Percentage Difference to evaluate the performance of the models.

## Methodology

- We made inferences about the relationship between different features of a house and its sale price by analyzing the data in the Ames Housing Dataset.
- We gained insights into how different features of a house, such as the number of bedrooms or the size of the garage, affect its sale price.
- We identified the important features affecting the sale price of the house.
- We applied L1 and L2 regularization techniques to prevent overfitting and improve the model's generalization performance.

## Results

- Linear Regression outperformed GBT and Random Forest models in terms of RMSE and R-square values, with a RMSE score of 20741.52 and a R-square of 0.91.
- The most important features affecting the sale price of the house were found to be the exterior quality of the house, ground living area, full bath and lot area of the house.
- The model achieved a low R-square value of around 0.86 and also a high mean percentage difference of 11.77% in the case of the Random Forest model.
- Gradient Boosted Trees outperformed Linear Regression and Random Forest models in terms of mean percentage difference of 6.77%.
- The important features for the model were found to be the quality of the house, the second floor area of the house, the lot area, and the exterior quality of the house.
- Linear Regression showed the highest R-squared values of 0.90 whereas GBT showed the lowest R-squared value of 0.82.
![image](https://user-images.githubusercontent.com/7029092/235245777-d95d996a-734c-4d95-94b1-7c0764ea4b24.png)

## Conclusion

By performing the predictions and inferences, we found out that Linear Regression showed the highest Rsquared value and the lowest RMSE values whereas Gradient Boosted Trees showed the least mean percent difference. The information gained from this project can be useful for understanding the real estate market, for making investment decisions, and for designing new houses that are likely to have high resale values.
