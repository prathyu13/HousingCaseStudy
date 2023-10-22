# HousingCaseStudy

Using regularization techniques like Ridge and Lasso, predict the price of a house

## Table of Contents

- [Problem Statement](#problem-statement)
- [Conclusions](#conclusions)
- [Technologies Used](#technologies-used)

## Problem Statement

A US-based housing company named Surprise Housing has decided to enter the Australian market. The company uses data analytics to purchase houses at a price below their actual values and flip them on at a higher price. For the same purpose, the company has collected a data set from the sale of houses in Australia. For the same purpose, the company has collected a data set from the sale of houses in Australia.

The company wants to know:

1. Which variables are significant in predicting the price of a house, and
2. How well those variables describe the price of a house.

Also, determine the optimal value of lambda for ridge and lasso regression.

## Conclusions

We aimed to capture the relation between the target variable "SalePrice" and several predictor variables. The model's primary goal was to provide accurate predictions of price of a house by applying regularization techniques like Ridge and Lasso Regression.

- **Model Performance**

Ridge Regression and Lasso Regression outperform Linear Regression with RFE in terms of R2 Score (both on the training and test datasets) and have lower Mean Squared Error (MSE) values. These results suggest that Ridge and Lasso Regression are providing better fits to the data and better generalization to the test dataset compared to the basic Linear Regression model.
Additionally, **Ridge Regression** has the lowest RSS (Residual Sum of Squares) on the test dataset, indicating **good model fit**.

- **Features Importance**

As per our final model, **top 3 features** that are significant in predicting sales price of houses are:

1. **GrLivArea** : One unit increase in GrLivArea variable increases the price of house by 0.09 / 0.10 units. Higher ground living area square feet are associated with higher house prices.

2. **OverallCond_9** : One unit increase in OverallCond_9 variable increases the price of house by 0.09 / 0.13 units. Higher the rating of house condition, higher the house price.

3. **Neighborhood_Crawfor** : One unit increase in Neighborhood_Crawfor variable increases the price of house by 0.08 / 0.10 units. The house prices are higher in the neighborhood of Crawford.

- **Optimal Value of alpha**

Ridge : 9.0
Lasso : 0.001

## Technologies Used

- Python

## Contact

Created by [@prathyu13] - feel free to contact me!
