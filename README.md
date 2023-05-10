# credit-risk-classification Report

## Overview of the Analysis

This analysis aims to develop a machine-learning model that can predict high-risk loans based on historical lending data. The lending data includes various features such as loan amount, interest rate, and borrower's credit score.
The goal was to build a model with high precision and recall scores to minimize the number of false positives and false negatives.

## Results

Machine Learning Model 1 (without oversampling):
Accuracy: 0.99
Precision:
Label 0 (healthy loan): 1.00
Label 1 (high-risk loan): 0.87
Recall:
Label 0 (healthy loan): 1.00
Label 1 (high-risk loan): 0.89

Machine Learning Model 2 (with oversampling):
Accuracy: 0.99
Precision:
Label 0 (healthy loan): 0.99
Label 1 (high-risk loan): 0.99
Recall:
Label 0 (healthy loan): 0.99
Label 1 (high-risk loan): 0.99

## Summary

It's important to note that both models have high accuracy and precision for the healthy loans (label 0), but the recall for the high-risk loans (label 1) is lower in the first model than in the second one. This means that the second model is better at identifying high-risk loans, which is critical in this scenario.

Based on the results, I recommend using Machine Learning Model 2 (with oversampling) due to its higher recall for high-risk loans, which is critical in identifying loans that could potentially default. 
