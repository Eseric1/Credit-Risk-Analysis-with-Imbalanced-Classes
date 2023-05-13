# Credit Risk Analysis with Imbalanced Classes
## Overview of the analysis
The purpose of this analysis is to use a logistic regression model to predict the credit risk of borrowers from a peer-to-peer lending company. The challenge is that the dataset of historical lending activity is imbalanced, meaning that there are much more healthy loans than risky loans. Therefore, I will compare the performance of the model on the original imbalanced dataset and on a resampled dataset using the RandomOverSampler technique from the imbalanced-learn library.

## Methodology
### The following steps were performed to create and evaluate the logistic regression model:

* Split the data into training and testing sets using a random split.
* Create a logistic regression model with the original data and fit it to the training set.
* Make predictions using the testing set and evaluate the model performance using metrics such as balanced accuracy score, confusion matrix, and classification report.
* Resample the training data using different techniques to address the class imbalance issue.
* Create a logistic regression model with the resampled data and fit it to the resampled training set.
* Make predictions using the testing set and evaluate the model performance using the same metrics as before.
* Compare the results of the original and resampled models and provide recommendations.