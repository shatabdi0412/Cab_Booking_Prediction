# Predicting Cab Booking Demand

This project was part of my PG Diploma in Artificial Intelligence and Machine Learning from NIT Warangal( jointly with Edureka )course

# Basic details about the problem :

A cab booking system is the process where renting a cab is automated through an app throughout a city. Using this app, people can book a cab from one location to another location. Being a cab booking app company, exploiting the understanding of cab supply and demand could increase the efficiency of their service and enhance the user experience by minimizing waiting time.

The objective of this work is to combine historical usage patterns along with open data sources like weather data to forecast cab booking demand in a city.

# Data :

- Hourly renting data span of two years is provided. Data is randomly divided into train and test sets. We must predict the total count of cabs booked in each hour covered by the test set, using the 
  the information available before the booking period.
- Here train labels i.e. ‘Total_booking’ are provided in a separate CSV file & we must append them to the train dataset before building the model.
- Descriptions of the columns present in the datasets as below.

  * DateTime- hourly date +timestamp
  * season- spring, summer, autumn, winter
  * holiday- whether the day is considered a holiday
  * workingday- whether the day is neither a weekend nor holiday
  * weather- Clear , Cloudy, Light Rain, Heavy temp-temperature in Celsius
  * atemp- "feels like" temperature in Celsius
  * humidity- relative humidity
  * windspeed - wind speed
Total_booking - number of total booking

# Model building:

1. Visualize data using different visualizations to generate interesting insights.

2. Outlier Analysis

3. Missing value analysis

4. Visualizing Total_booking Vs other features to generate insights

5. Correlation Analysis
   
6. Visualizing Total_booking Vs other features to generate insights 

Task2:

1. Feature Engineering

2. Model Building
  (Different models regression analysis)

3. Grid search

4. Model Selection

5. Testing the trained model on 'test.csv'


# Dependencies:

Python 3+, jupyter notebook, Pandas, Numpy, EDA, Sklearn, Supervised learning, Linear regression, Ensemble learning, Decision tree, Random forest, SVR, Bagging, Adaboost, Gradientboost

# Purpose:
The purpose of this project is to gain insights into the following topics

# Pratical implementation of -

* EDA analysis of data
* Outlier detection & removal
* finding missing values & replacing with suitable values
* plotting of various features on graphs for better intuition using Seaborn & Matplotlib
* correlation analysis using heatmap
* feature engineering
* ML algorithms & Ensemble learning

# Conclusion:
- This work can be directly used for predicting the cab booking system for any practical applications

- The above procedure will be the same for any ML model building & it can be taken as a reference for other works also
