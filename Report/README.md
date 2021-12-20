# Cardiovascular Disease Prediction.

Mashael  Alfehaid - Hala Alanazi

____

## Overview
This project worked on a data set containing an Cardiovascular disease , It was collected at the time of the medical examination. The goal of this project is to build machine learning models to classify or identify patient's condition on Cardiovascular Disease based medical examination for the patient.

## Goals

- Build a classification model to predict Cardiovascular Disease.
- Choose the model that give us the best accuracy.

## Methodology


1- Loading the dataset.

2- EDA (cleaning and visualizing the data).

3- Building different classification Models.

4- choosing the model based on given best accuracy to prediction.

## Dataset

We used a dataset of Cardiovascular Disease from Kaggle website [here](https://www.kaggle.com/sulianova/cardiovascular-disease-dataset)
- The dataset contains 70,000 observations and 13 features.


Our EDA steps :
- Dropped all duplicated and unneeded rows and columns.
- Rename columns.
- Remove outliers .
- convert [age] from days to years.
- Converted categorical data into numeric.
- Numeric and categorical data visualization.

After cleaning the data set the rows became 61,296 and columns are 24.

#### Feature Engineering:
we bulied multbl of features:
- BMI measure of body fat based on height and weight and put it into category
- Ratio between systolic blood pressure and diastolic blood pressure
- Relationship of pressure with weight
- Put the age column into category
- Put blood pressure  columns into category

#### Model Building: 
Over 8 models were tried and played with to get the best model that goes hand in hand with the dataset. After performing simple train and validation on the  models one was chosen for further investigation. Models trained was:

- Logstic regression (Baseline)
- MLP Classifier
- knn 
- Decision Tree 
- Naive Bayes (GaussianNB)
- Random forest
- XGB Classifier
- Ensemble Methods (Max Voting, Average Voting, and Stacking Classifier)


The Best 3 Models:  XGB Classifier , Stacking Classifier and MLP Classifier

</br>
- Dealing with low accuracy by using featuers selection.
</br>
- Evaluating gridsearch for the best models

#### Tools:
- Jupyter notebook
- Numpy 
- Pandas 
- Matplotlib 
- Seaborn  
- Sklearn
- Jupyter notebook

