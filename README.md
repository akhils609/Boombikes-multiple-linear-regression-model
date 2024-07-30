# Project Name
> BoomBikes : Regression Modelling Problem  


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)



## General Information
- Provide general information about your project here.
- What is the background of your project?
BoomBikes is a bike-sharing service that has faced significant revenue challenges due to the ongoing COVID-19 pandemic. As the lockdowns begin to lift and the economy starts to recover, BoomBikes aims to reposition itself to capture and respond to the anticipated surge in demand for shared bikes. To achieve this, the company seeks to understand the factors that influence bike demand and how these factors may change as the pandemic subsides. This understanding will help BoomBikes tailor its services to meet the evolving needs of its customers and enhance its competitive edge in the market.
- What is the business problem that your project is trying to solve?
The primary business problem is to develop a predictive model that can accurately forecast bike demand based on various influencing factors. 
This model will help BoomBikes:
Identify Key Drivers of Demand: Understand which variables have the most significant impact on bike demand.
Optimize Resource Allocation: Adjust bike distribution, pricing strategies, and service hours to align with demand patterns.
Improve Strategic Planning: Plan marketing efforts and operational strategies based on anticipated changes in bike demand.

- What is the dataset that is being used?
The dataset used for this project includes daily bike demand data, which is supplemented by various independent variables that are likely to affect bike usage. 
The key components of the dataset are:
Daily Bike Demand: The number of bikes rented or used each day, which serves as the target variable for prediction.
Independent Variables: These include factors that might influence bike demand. Common features in such datasets might include:
Weather Conditions: Variables such as temperature, humidity, precipitation, and wind speed.
Temporal Information: Day of the week, time of day, season, and special events or holidays.
User Type: Information on whether the bike user is a casual or registered user.



## Conclusions
- Temperature and ambient temperature variables are correlated to the target variables 
- Holidays also have significance towards usage of usage of services
- We also see that there's an increase in the usage of services over the year indicating years of service is also a significant variable for prediction
- A Multi linear regression was built using statsmodels api , with 17 features with train set r-square value 0f 0.843 and test accuracy 0.81
- Variable selection was done using VIF and significance 




## Technologies Used
- pandas - version 2.1.4
- NumPy - version 1.26.4
- seaborn - version 0.13.1
- statsmodels-version 0.14.2
- sklearn - version 1.3.2




## Contact
Created by [@akhils609] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->