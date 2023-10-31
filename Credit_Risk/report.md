# Module 12 Report

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The objective of this analysis is to assess the effectiveness of two models designed to predict the creditworthiness of borrowers. The dataset utilized for training and testing these models was sourced from a peer-to-peer lending company and includes variables such as loan size, interest rate, borrower's income, debt-to-income ratio, the number of accounts held by the borrower, derogatory marks associated with the borrower, total debt of the borrower, and loan status.

The loan status data was extracted from the original dataset, and separate training and testing datasets were generated for model training and evaluation. The first model retained the unbalanced ratio of healthy and high-risk loans as in the original dataset for training. The second model, however, was trained on data that underwent preparation using the RandomOverSample module to ensure an equal number of data points for each label (healthy - 0, and high-risk - 1). Subsequently, logistic regression models were constructed and trained for making predictions.

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Accuracy: 95%
  * Precision: healthy - 100% ; high-risk - 85%
  * Recall: healthy - 99% ; high-risk - 91%

* Machine Learning Model 2:
  * Accuracy: 99%
  * Precision: healthy - 100% ; high-risk - 84%
  * Recall: healthy - 99% ; high-risk - 99%

## Summary

Machine Learning Model 2 is the preferable choice due to its superior overall accuracy, particularly in its capacity to accurately detect high-risk loans 99% of the time, surpassing the 91% achieved by Model 1.

If you do not recommend any of the models, please justify your reasoning.
