# Ensembling-Heart_failure_prediction

## Overview
This is a simple Classification problem to predict whether an individual will be prone to heart failure or not. The trained model takes few criteria like Age, Sex, Diabetes, Hypertension, Creatinine, Platelets count, Anaemic, Sodium content and Smoking factor as input and determines Yes/No for Heart Failure using Ensembling Algorithms.

## Technical Aspect

## Ensembling Techniques
Its the process of combining multiple models to predict the final outcome. There are three different techniques in Ensembling,

### 1. Bagging - (Boostrap Aggregation)
--> Data is split and fed to various Base Learners for processing. This method is know as Boostrap. The splitting up of data occurs by a process called Row Sampling with Replacement.

--> The various Base learners processes the data and predicts the outcome.

--> The outcome of all these Base learners are then collectively used to predict the final outcome of the Ensemble model. This process is known as Aggregation.

--> Aggregation generally happens by the method of Voting Classifier, which is a process of predicting the outcome based on the majority of the outcome of Base learners.

--> Voting Classifier is generally of 2 types

  --> Hard Voting Classifier - Selects the value which occurs maximum number of times
  
  --> Soft Voting Classifier - Instead of selecting the value, it checks for probabilities (the one with higher probablitiy is chosen).

#### Random Forest - technique of Bagging using Row Sampling with Replacement
#### Extra Trees Classifier - technique of Bagging but using Row Sampling without Replacement

### 2. Boosting

--> Its a technique where the Base Learners are sequential. That is, the Data is fed to the first Base Learner and the outcome of which is fed to a next Base learner and continues sequentially upto a certain depth.

--> When the data with High Bias and Low Variance is passed to the 

### a) Input
1. Age
2. Sex
3. Creatinine
4. Anaemia
5. Platelets count
6. Diabetes
7. Blood Pressure
8. Sodium
9. Smoking habit

### b) Output
1. Yes - Prone to Heart Failure
2. No - Not Prone to Heart Failure

### c) Data Analysis
1. Missing values
2. Outlier detection
3. Feature Engineering - Feature Selection (Select KBest, Chi square, Pearson Correlation, p-value)
4. Feature Scaling - Standard Scaler 
5. Hyperparameter tuning

### d) Algorithms used
1. Random Forest 
2. Extra Trees Classifier
3. AdaBoost
4. Gradient Boosting
5. Extreme Gradient Boosting

### e) Accuracy
Metrics - Accuracy score

### f) Programming Language 
Python

### g) Framework
Jupyter Notebooks


## Credits
Kaggle - Source of dataset which saved my time for Data Collection
