# Bike Sharing Assignment

#### Problem Statement
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes. How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.


## Table of Contents
* [General Info](#general-information)
* [Data Sets Used](#data-sets-used)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)


## General Information

#### Business Goal
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Conclusions
- All the positive coefficients like temp,season_Summer indicate that an increase in these values will lead to an increase in the value of cnt.
- All the negative coefficients indicate that an increase in these values will lead to an decrease in the value of cnt.
- Temp is the most significant with the largest coefficient followed by weathersit_Light Snow & Rain. 
- Bike rentals is more in the month of september and is reduced during the holidays. 
- Bike rentals are majorly affected by season, month and temperature.


## Data Sets Used
- day.csv - Contains all data for analysis
- Data_Dictionary.txt - Contains the metadata

## Technologies Used
- Python


## Contact
Created by [@anshuman-acharya] - feel free to contact me!
