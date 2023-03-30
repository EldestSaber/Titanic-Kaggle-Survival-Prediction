# Titanic - Machine Learning from Disaster
## Introduction
This repository contains an end-to-end analysis and solution to the Kaggle Titanic survival prediction competition. This is a collection of my predictions of the solution to the competition. This notebook contains comments on the code that explains the processes used to form a solution to the problem presented by the competition.
## Problem statement
Given what we know about a passenger aboard the Titanic, can we predict whether or not this passenger has survived? In other words, we are training a machine learning model to learn the relationship between passenger features and their survival outcome and susbsequently make survival predictions on passenger data that our model has not been trained on.

This is a binary classfication problem in machine learning as we are classifying the outcomes of passengers as either survived or did not survive the Titanic.
## Data description
Below is a description of the features and the label of the dataset.
## Evaluation metric
The evaluation metric of this competition is the percentage of passenger data in the test set that are correctly predicted by the model. This is known as accuracy.
### Features:
- Pclass - Ticket class (1 = First class, 2 = Second class, 3 = Third class)
- Sex - Sex (male or female)
- Age - Age in years
- Sipsp - Number of siblings/spouses aboard the Titanic
- Parch - Number of parents/children aboard the Titanic
- Ticket - Ticket number
- Fare - Passenger fare (USD)
- Cabin - Cabin number 
- Embarked - Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
### Label:
- Survived - Whether or not the individual survived (0 = did not survive, 1 = survived)
