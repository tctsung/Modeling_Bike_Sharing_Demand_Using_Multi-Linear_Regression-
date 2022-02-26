# Modeling_Bike_Sharing_Demand_Using_Multi-Linear_Regression-

## Introduction

Bike sharing system is one of the most trending ways for communication and traveling due to its flexibility and convenience. According to Wikipedia, there are currently more than 500 bike sharing system worldwide in more than 1000 cities. This generates a big market and rises peoples’ interest in analyzing the customers preference in bike rental. In this project, we utilize multi-linear regression, a statistical method for predicting continuous outcome based on two or more input variables, to predict the count of total rental bikes per hour in [UCI Bike Sharing](https://archive.ics.uci.edu/ml/datasets/bike+sharing+dataset) Data set. The outline could be broadly separated to descriptive statistics, two common methods for multi-linear modeling, a series of detailed regression diagnostics, and model transformation.

- keywords: multi-linear regression, regression diagnosis


* [Data tidying](https://github.com/tctsung/Modeling_Bike_Sharing_Demand_Using_Multi-Linear_Regression-/blob/main/data_tidying.Rmd)
  * Data cleaning and descriptive statistics
* [Regression modeling](https://github.com/tctsung/Modeling_Bike_Sharing_Demand_Using_Multi-Linear_Regression-/blob/main/modeling.Rmd)
  * Established multi-linear model by exhaustive search or stepwise selection  
  * Using AIC, BIC, adjusted R^2 as criteria with correlation and VIF-based feature selection 
* [Diagnosis](https://github.com/tctsung/Modeling_Bike_Sharing_Demand_Using_Multi-Linear_Regression-/blob/main/diagnosis.Rmd)
  * Included content: constant variance, normality, collinearity, leverage points, outliers and influential points
* [Transformation](https://github.com/tctsung/Modeling_Bike_Sharing_Demand_Using_Multi-Linear_Regression-/blob/main/transformation.Rmd)
  * model with interaction and polynomial
  * outcome log-transformation and box-cox transformation

**source of data**

- UCI Machine Learning Repository [Bike Sharing Dataset](https://archive.ics.uci.edu/ml/datasets/Bike+Sharing+Dataset?fbclid=IwAR3uiFUh-wHIXccZQAMOIoPsDfru40yv8Lnuh-1n2D7x1oyTsUPcpAq-X4k)
