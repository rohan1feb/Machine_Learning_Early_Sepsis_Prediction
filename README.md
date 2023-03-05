# Machine_Learning_Early_Sepsis_Prediction

Sepsis is the body’s overwhelming and life-threatening response to infection that can lead to tissue damage, organ failure, and death. The numbers are alarming and are estimated to be 11.3 million cases with 2.9 fatalities in India itself in 2017. SOFA (Sequential Organ Failure Assessment) score >= 2 points is identified as organ dysfunction consequent to the function.

## Dataset

There is a csv with patient information of 790215 patients.
There are a total of 43 features being measured.

## Requirement

Understanding of data science framework and use of all algorithms / techniques (supervised or unsupervised) discussed in class or lab.
Predict sepsis diagnosis 6 hrs and 12 hours prior to sepsis manifestation!

## Approach

We performed exploratory data analysis on the dataset.
We did a lot of domain research.
We performed pre-processing steps - dropping columns, imputation, feature engineering, and creating composite features.
We have oversampled the data as there was a data imbalance
We have applied multiple machine learning algorithms (logistic regression, decision tree, random forest, Adaboost, XGboost etc) to predict the onset of sepsis
We have use data explainability techniques for our model
