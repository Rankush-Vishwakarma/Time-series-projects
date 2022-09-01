# Time-series-projects
   This Repo is based on time-series data set , analysis and predictions.

# Introduction
   The goal of this project is to take the publically available Beijing weather data from 2013 to 2017 and apply Time Series techniques to see if we can predict the amount of PM2.5 concentration in the air given other environmental features. This is a project I am working on during my free time applying some of the machine learning algorithms I have learned. I hope to come up with a predictive model with a high accuracy and a very low Root Mean Square Error (RMSE).


# Dataset Information
   This data set includes hourly air pollutants data from 12 nationally-controlled air-quality monitoring sites. The air-quality data are from the Beijing Municipal Environmental Monitoring Center. The meteorological data in each air-quality site are matched with the nearest weather station from the China Meteorological Administration. The time period is from March 1st, 2013 to February 28th, 2017. Missing data are denoted as NA.


# Project workflow
   This project utilizes the Time Series model. The model we hope to succeed in training is a regression model and below are the steps we will go through in this colab notebook for this project:

# Import the neccessary libraries and loading the data
   Data preprocessing
   Exploratory Data Ananlysis
   Seasonality Checking
   Model Fitting using ARIMA
   Saving the model
