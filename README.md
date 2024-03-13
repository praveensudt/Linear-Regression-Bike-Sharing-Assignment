# Bike Sharing Assignment
> Identify the risky loan applicants, then such loans can be reduced thereby cutting down the amount of credit loss. Identification of such applicant's using EDA is the aim of this case study

## Table of Contents
* [General Info](#general-information-and-problem-statement)
* [Business Goal](#business-goal)
* [Conclusions](#conclusions)
* [Technologies Used](#technologies-used)
* [Acknowledgements](#acknowledgements)

## General Information and Problem Statement
- A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
- In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.
- They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. 
- The company wants to know, which variables are significant in predicting the demand for shared bikes, How well those variables describe the bike demands. Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

### Business Goal:

We are building a model to identify the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 

The model should be built taking this 'cnt' as the target variable

## Conclusions
Final analysis,
- R-Squared for test data : 0.81
- Adjusted R-Squared for test data : 0.80
- R-Squared for train data : 0.84
- Adjusted R-Squared for train data : 0.84

Bikes rental demand is based on the variables year, holiday, temp, windspeed, spring, summer, winter, sep, sun, Light_snow, Mist 

## Technologies Used
- pandas - version 2.2.0
- numpy - version 1.26.3
- matplotlib - version 3.8.2
- seaborn - version 0.13.2
- Scikit-learn - version 1.4.1.post1
- Statsmodels - version 0.14.1

## Acknowledgements
- This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course
