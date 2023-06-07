# deep-learning-challenge
# credit-risk-classification


## Overview of the Analysis

The analysis uses a dataset of historical funding activity for the nonprofit foundation Alphabet Soup wants a tool that can help it select the applicants for funding with the best chance of success 

* The model is design to predict the success of applications by using the "IS_SUCCESSFUL" feature of the dataset.
* The stages of the machine learning process include creating the X and Y elements, seperate the training and test data, standardized the data through Standardscaler, trained the model, and then resampled the data.
* The methods used were multiple `Sequential` model and 'Kesturner' model method.

## Results

The balanced accuracy scores and the model loss for 'Sequential' machine learning models.

* Machine Learning Model 'Sequential' with two models with different cutoff, features and variables:
  *Model 1:
   Loss: 0.5537437796592712, Accuracy: 0.7246647477149963
  *Model 2:
   Loss: 0.5558030009269714, Accuracy: 0.7251312136650085

  * Machine Learning Model 'Kesturner':
   Loss: 0.5558030009269714, Accuracy: 0.7251312136650085

## Summary

Summary the results of the machine learning models, and recommendation none of the model to use:
* The Sequential model was able to prodict the applications sucess to an approximent 72 percent accurary.
* Multiple variations of the features used to create the model as well as multiple attemptes at different cutoffs all resulted in similar results.  No results were able to improve the accuracy but same did result in over fitting the model and a decrease in the results.
* The Kesturner was run to insure that the optimized number of levels and activiation was used and also resulted in similar results.  
* The results found with the available data and created models did not produce statisfactoyry confidence to sucessfully predict the sucess of the applications.






# CHALLENGE

## Background
In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Instructions
The instructions for this Challenge are divided into the following subsections:

## Split the Data into Training and Testing Sets

Create a Logistic Regression Model with the Original Data

Predict a Logistic Regression Model with Resampled Training Data

Write a Credit Risk Analysis Report

Split the Data into Training and Testing Sets

Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.

Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.

Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:

Fit a logistic regression model by using the training data (X_train and y_train).

Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.

Evaluate the model’s performance by doing the following:

Calculate the accuracy score of the model.

Generate a confusion matrix.

Print the classification report.

Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?