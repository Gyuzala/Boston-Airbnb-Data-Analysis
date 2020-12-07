# Project-1: Udacity Boston Airbnb Data Analysis

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#project-motivation)
3. [File Descriptions](#file-descriptions)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing-authors-and-acknowledgements)


## Installation 

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.*.

## Project Motivation 

This entire project is part of a Data Scientist Nanodegree Program by Udacity. The project aimes to apply CRISP-DM process in analytics of data of my choice. I have chosen the [Boston Airbnb Data]. Using this data I have tried to answer the following questions:

1. What is the most popular listing by room type in Boston?
2. What is the most popular neighbourhood in Boston among renters?
2. Is it possible to predict the price of a listing and what are the main features for price prediction?

[Boston Airbnb Data]: https://www.kaggle.com/airbnb/boston 

## File Descriptions

There is one Jupyter Notebook file that contains all the analytics and codes. Markdown cells were used to assist in walking through the thought process for individual steps.

## Results

You can find brief results below, for more detailed answers please refer to my [blog post here]: 

[blog post here]: 

1. What is the most popular listing by room type in Boston?

Surprisingly, the most listed property by room type in Boston is the listing of ***Entire Home or Apartment*** and not the ***Private Room*** , having 59% market share against 38%. It is also well proven with the annual availability data which tells us that the ***Entire Home or Apartment*** is available up to 175 days in a year against 225 days of the ***Private Room*** . 

2. What is the most popular neighbourhood in Boston among renters?

The Mission Hill is the most popular neighbourhood in Boston among Airbnb renters, it is well explained with the amount of people leaving reviews, the average price and the annual availability. While the least popular area in Boston is Leather District, which has only 50 reviews against 400 of Mission Hill, having average price of 250 per night vs 120 of Mission Hill.

3. Is it possible to predict the price of a listing and what are the main features for price prediction?

It is possible to predict prices of Airbnb listings with the given data, the XGBoost model has been used with the accurracy score of 86% on the train data and performing 72% accuracy on the test data. 
The TOP 3 features for price prediction appeared to be: 
* Room type 
* Number of bedrooms
* The number of people the property can accomodate

## Licensing, Authors, and Acknowledgements

Licensing for the data and other descriptive information at the [Kaggle link available here].

[Kaggle link available here]: https://www.kaggle.com/airbnb/boston

