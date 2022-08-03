# Use of Decision Tree Classifier in Predicting Future Customers
## Introduction
This project uses a dataset from Kaggle, which can be found here https://www.kaggle.com/datasets/arnabdata/suv-purchase-decision. The dataset has the following attributes:
* User ID.
* Gender.
* Age.
* Estimated salary.
*Purchased.
The attributes that will be used for this project are age and gender as the independent variables whereas purchased will be the dependent variable

## Objectives
The main objective is to fit a decision tree classifier to provide predictions for future customers.

## Libraries used.
* Numpy.
* Pandas.
* Matplotlib.
* Scikit learn.

## Methodology
The first step was to identify the dependent and independent variables, then split them into training and testing sets. Feature scaling was done through standardization to make sure no variable dominates the others while also putting the variables on the same scale. A decision tree was fitted on the training dataset and the confusion matrix is as shown below.
