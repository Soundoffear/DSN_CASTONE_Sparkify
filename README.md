# Sparkify - Data Science Nanodegree CAPSTONE

## Overview of Project

The project in this repository is CAPSTONE from [Udacity](udacity.com) Data Science Nanodegree, it contains jupyter notebook that contains all the code for each part required to pass the projects.

The assigment of the project was to identify users, of the fictional service called Sparkify, that would churn away from the service. The data contained within the project itself had variety of different variables both numerical and categorical, that required to be cleaned, transformed, processed in order to get each part of the project required.

## Required steps

1. Read and clean the data
2. Exploratory Data Analysis
3. Feature Engineering
4. Machine Learning - Classification of users

## Required packages

* Pandas - data analytics library
* numpy - data analytics and processing library
* matplotlib - data visualization library
* pyspark - Python API written in python to support Apache Spark, which is distributed framework for processing Big Data analysis
* seaborn - build on top of matplotlib visualization library allowing to customize plots a little bit faster

## Results of the project

After loading, cleaning, exploring data and feature engineering four classifiers have been trained:
- Logistic Regression Classifier
- Support Vector Classifier
- Random Forest Classifier
- Boosted Trees Classifier

All the classifiers were run on dataset with 21 featres and data set with 29 features, in order to compare how number of features influences the accuracy of the prediction, even with only 8 new features have been added.

The results with details can be found in article below:
https://medium.com/@m.dyngosz/sparkify-will-churn-or-will-not-churn-this-is-the-question-88a1b2668283?sk=3d3bc4503dfcc6c6435b97baee2a689e

## Included Files
README.md - read me file
Sparkify.ipynb - notebook with all the code used for this project
