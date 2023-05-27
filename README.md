# Advanced Regression-House Price Prediction

## Business Objective:
A US-based housing company called Surprise Housing has decided to enter the Australian market. The company wants to purchase houses at a price below their actual values and sell them on at a higher price. The company has collected a data set from the sale of houses in Australia.It is looking at prospective properties to buy to enter the market. We are required to build a regression model using regularisation in order to predict the actual value of the prospective properties and decide whether to invest in them or not.The company wants to know:

  1.Which variables are significant in predicting the price of a house and how well those variables describe the price of a house.
  2.We have to determine the optimal value of lambda for ridge and lasso regression.
 
## Table of Contents
* [Dataset](#Dataset)
* [Technologies](#Technologies)
* [Conclusions](#Conclusions)
* [Contributors](#Contributors)


## Dataset
- 'train.csv' dataset is used.It is dataset from the sale of houses in Australia. 

## Technologies
- Python-3.7.3
- Pandas-0.24.2
- Numpy-1.16.4
- Matplotlib-3.1.0
- Seaborn-0.9.0
- Scikit-learn-0.21.2

## Conclusions
- The optimal value of lambda for Ridge=20, Lasso=500.
- Top Features as per Ridge Regression are:
            1.MSSubClass
            2.Neighborhood_NridgHt
            3.Neighborhood_OldTown
            4.OverallCond
            5.BsmtFullBath
            6.BsmtExposure_Mn
            7.Exterior1st_AsphShn
            8.Neighborhood_Edwards
            9.LowQualFinSF
            10.Condition1_PosA
- Top Features as per Lasso Regression are:
            1.MSSubClass
            2.Neighborhood_NridgHt
            3.BsmtFullBath
            4.Neighborhood_OldTown
            5.OverallCond
            6.BsmtExposure_Mn
            7.Condition1_PosA
            8.GarageArea
            9.Neighborhood_Edwards
            10.YearRemodAdd

## Contributors
Created by [@rakeshrau] - Rakesh Raushan
