# San Francisco Crime Classification (Kaggle) using Spark and logistic regression

## Overview
The "San Francisco Crime Classification" challenge, is a [Kaggle](https://www.kaggle.com) competition aimed to predict the category of the crimes that occurred in the city, given the time and location of the incident.


Link to the competition: [San Francisco Crime Classification](https://www.kaggle.com/c/sf-crime)

## Data
The competition provides two dataset: a train data set and a test dataset. The train dataset is made of 878049 observations and the test dataset, of 884262 observations.

Both of them contains incidents from January 1, 2003 to May 13, 2015.

##Data fields

Dates : timestamp of the crime incident.
Category: Category of the incident. Also, this is the variable we want to predict. This variable is available only in the train dataset.
Descript: A short description of the incident. This variable is available only in the train dataset.
DayOfWeek: Day of the week where the incident occurred.
PdDistrict: Police Department District
Resolution: Outcome of the incident. This variable is available only in the train dataset.
Address: Address of the incident.
X: Longitude
Y: Latitude

## Learning method

The algorithm chosen for the implemented solution, is a [multinomial logistic regression](https://en.wikipedia.org/wiki/Multinomial_logistic_regression), a classification model based on regression where the dependent variable (what we want to predict) is categorical (opposite of continuous).

