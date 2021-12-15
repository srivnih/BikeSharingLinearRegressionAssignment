
# Bike Sharing Assignment - Linear Regression
This is a assignment to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 


## Table of Contents
* [Steps followed for Model Building](#steps-followed-for-model-building)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)

## Steps followed for Model Building
1.Reading and Understanding Data
2.Visualising the Data
3.Data Preparation
4.Splitting the Data into Training and Testing Sets
5.Feature Scaling
6.Building the Model
7.Residual Analysis of the train data
8.Making predictions using final model
9.Model Evaluation

## Conclusions
From the regression model we can conclude the below :-
1. All positive co-efficients indicate that with the increase in the variable values the target variable 'cnt' will increase (e.g. temp, yr, season-winter, mnth-Sep)
2. All negative co-efficients indicate that with the increase in the variable values the target variable 'cnt' will decrease (e.g. mnth-July, holiday, season-spring, windspeed, weathersit-Light Snow)
3. 'temp' is the most significant variable for target variable 'cnt' as it has highest co-efficient
4. The target variable 'cnt' reduces during Light Snow, Light Rain + Thunderstorm + Scattered clouds weather,  windspeed & holidays
5. The target variable 'cnt' is more during yr (2019) , winter and in mnth-Sep

## Technologies Used
Python 3.8.8
Jupyter Notebook 6.3.0
Git 2.33.1.windows.1

## Contact
Created by [@srivnih] - feel free to contact me!