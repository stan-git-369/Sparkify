# Udacity Nanodegree Capstone Project - Sparkify

## Table of Contents
1. Installation
2. Project Motivation
3. File Descriptions
4. Models
5. Result
Acknowledgement

## Installation
You will need Pyspark SQL and Pyspark MLPython, also Pandas, Matplotlib, Seaborn. The code should run with no issues using Python versions 3.*.

## Project Motivation
This is Udacity's Capstone Project, using spark to analyze user behavior data from music app Sparkify. The main goal is to predict churns based on user log data(a tiny subset (128MB) of the full dataset available (12GB)) from a music app. The log contains some basic information about the user as well as information about a single action. A user can contain many entries. In the data provided, a part of the user is churned, that can be distinguished through the cancellation of the account.

## File Descriptions

Sprakify.ipynb: main file of the project, a jupyter notebook contains of exploratory data analysis, feature engineering and modeling to predict churns.

, and which is exported into Sparkify Project.html.

## Models
The follows models are used for classification of users: Logistic Regression, Decision Trees,  Gradient Boosted Trees

## Result
The data provided is the user log of the service, having demographic info, user activities, timestamps and etc. We try to analyze the log and build a model to identify customers who are highly likely to quit using our service, and thus, send marketing offers to them to prevent them from churning. We use F1 score to measure of model performance because we need precision and recall at the same time as we don't want to miss too many customers who are likely to churn whilst we don't want to waste too much on those who are not likely to churn. The model we built has a F1 score of 0.79, which is 14% higher than sending everybody offers. There is also a short article about this project posted here.

## Acknowledgement
Must give credit to Udacity for the project.
