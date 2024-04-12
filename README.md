# Bike Sharing Assignment
This is about building a multi linear regression model for the prediction of demand for shared bikes.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
- Business Objective
                The objective is to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands   vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.
  
- Data Set Details
                The data set consists of varius features called as input variables mentioned below and target variable 'cnt' which indicated the demand of the shared bikes.
  instant	dteday	season	yr	mnth	holiday	weekday	workingday	weathersit	temp	atemp	hum	windspeed	casual	registered	cnt
  
- Model Details
                Machine Learning approach is used to model this system.This comes under Multi Linear Regression model.Below are the steps followed in this approach to model the system.
  - Step 1: Reading and Understanding the Data
  - Step 2 : Visualizing the data
  - Step 2 : Preparing data for modeling
  - Step 3: Training the Model
  - Step 4: Residual Analysis
  - Step 5 : Test Data preparation and Evaluating the model using Test data

## Conclusions
- Following Input variables are considered as significant in predicting target variable cnt. 
        'yr', 'temp', 'spring', 'winter', 'july', 'nov', 'sept', 'weathersit_2', 'weathersit_3'
- Train Data R-Squared value : 0.819
- Test Data R- Squared value : 0.813
- Its evident that the model is trained well and it can be considered as best fit linear regression model.
- Equation : cnt = 0.19 + 0.23 yr + 0.47 temp - 0.12 spring + 0.06 winter - 0.06 july - 0.04 nov + 0.06 sept -0.07 weathersit_2 -0.3 weathersit_3

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Following libraries used
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - sklearn
  - statsmodels


## Contact
Created by @pamidipati - feel free to contact me!
