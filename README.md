# credit-risk-classification
Module 20 Challenge

## Instructions
The instructions for this Challenge are divided into the following subsections:

* Split the Data into Training and Testing Sets
* Create a Logistic Regression Model with the Original Data
* Write a Credit Risk Analysis Report

## Overview of the Analysis
The purpose of this analysis was to use historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. Financial information used included more than 77000 rows of data with the size of the loan, interest rate, income of the borrower, debt to income ratio, number of account the borrower holds, derogatory marks, total debt of the borrower, and whether the loan was a healthy loan or a high-risk loan. Based on this data, we are trying to create a model to predict whether a potential borrower is creditworthy. We used training data on loan status (healthy vs. high-risk) and fit the logistic regression model with the training data. 

Machine Learning Model 1: 
* Accuracy: 
* Precision: 1.00
* Recall: 1.00

Machine Learning Model 2:
* Accuracy:
* Precision: 0.87
* Recall: 0.89

For the healthy loan (0), the model predicts 100% on precision and and is correct 100% of the time; this model indicates perfect performance when predicting a healthy loan. For the high-risk loan (1), the model predicts correctly 87% of the time and correctly identifies actual high-risk loans 89% of the time. Perfect precision on 0 and strong performance on 1. 

This model performs well and is highly recommended to predict loan status for potential borrowers. 
