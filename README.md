# Sparkify - Predicting Churn from User Behavior

## Background and Motivation

For the Udacity Data Science NanoDegree, we were asked to complete a Capstone project to demonstrate our capability of handling and end to end machine learning project.
I chose to take on the <u>Sparkify</u> project, in which we attempt to predict customer churn from user behavior at the level of raw events.

Sparkify is a fictious music streaming service that logs every user action as an event. Faced with this voluminous data, the challenge is to use PySpark,
the Python API to Spark, to create meaningful features from raw data that allow us to predict which customers will cancel the service.

## Tasks
For this project we were tasked with completing: 
1. Loading and Cleaning the Data - load the data and check for missing values that would hinder analysis and modelling.
2. Exploratory Data Analysis - become familiar with the data and determine next steps in creating features
3. Feature Engineering - Create meaningful features from the raw event data
4. Preprocessing - pre-process the data as appropriate (encoding, imputing, scaling, etc)
5. Modelling - Build model(s) on the training data. Tune and select final models.
6. Evaluation - Discussion of model results and selection of best model

## Summary of Files and Folders
The main items of interest here are the two Jupyter notebooks, one of which was used to develop and explore in local mode on the smaller dataset.
The other notebook is an AWS EMR notebook that processed the full 12GB dataset. 
These notebooks contain all of the data exploration, analysis, and article recommendations as required by the project.
Finally, there is `wrangling.py`, which contains all the consolidated code to read in the dataset, create features, and train a model.
