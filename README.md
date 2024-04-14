## Module 20 Challenge
# credit-risk-classification
### File respoitory for challenge contains:
- credit_risk_classification.ipnyb
- Resources folder containing lending_data.csv
- Starter_Code folder containing original initially provided code

found at: https://github.com/TRegan5/credit-risk-classification

## Goal
Train and evaluate a model based on loan risk to identify creditworthiness of borrowers, using various techniques and a dataset of historical lending activity from a peer-to-peer lending services company.

## Methods
1. Split the Data into Training and Testing Sets
2. Create a Logistic Regression Model with the Original Data
3. Write a Credit Risk Analysis Report

## Credit Risk Analysis Report
### Analysis Overview
The purpose of this analysis is to classify the creditworthiness of borrowers based on a logistic regression model generated a hitorical lending activity dataset. Loan status of borrowers is classified as either `healthy` or `high risk`.

### Results
Results of the generated model produced the following classification scores:
- Accuracy score: 0.99; on a scale of 0 to 1.0, the provided classification model nearly perfectly predicts both `healthy` and `high risk` loans
- Precision score: 
    - Healthy loan status: 1.00; the model perfectly predicted all `healthy` loans as healthy
    - High risk loan status: 0.87; the model correclty predicts 87% of `high risk` loans, leaving 13% as falsely predicted high risk
- Recall score: 
    - Healthy loan status: 1.00; the model perfectly identified all actual `healthy` loans as healthy
    - High risk loan status: 0.89; the model correctly predictged 89% of all actually `high risk` loans as having high risk, leaving 11% of actual high risk loans in the data set not identified as such
### Summary
The provided credit crisk classifcation model predicts 18,679 loans as `healthy`  and 558 as `high risk`, with near pefect 0.99 accuracy. It perfectly predicts healthy loans with 1.00 precision and correctly identifies the actual healthy loans with 1.00 recall. It has slightly lower performance on correctly prediciting and identifying `high risk` loans, with 0.87 precision predicting and 0.89 recall identifying those loans actually having high risk. 

I hihgly recommend this model for use to do exceptionally strong ability to identify those borrowers deserving loans and very strong performance predicting risky borrowers. 