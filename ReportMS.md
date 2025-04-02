# Module 20 Report

## Overview of the Analysis

* **Purpose of Analysis** The goal of this analysis is to determine if the Logistic Regression machine learning model can more accurately predict healthy loans versus high risk loans using the original dataset or a dataset that is resampled to increase the size of the minority class.
* **The Dataset** The dataset used to perform the analysis consists of information on 77,536 Loans. The data includes columns for loan_size, interest_rate, borrower_income, debt_to_income ratio, number_of_accounts, derotatory_marks, total_debt, and loan_status. The category that we are trying to predict with our analysis is "loan_status". The data provided in the remaining columns will be used as features to train the data and inform the predictions.

-	Prepared the data- imported the file, established the dataframe, evaluate the columns and features.
-	Separate the data into features and labels - The labels are what you are attempting to predict, is the status of the loan (Healthy (0)) or high-risk (1). The features are all of the remaining data you will use to train and test the model.
-	Use the train_test_split function to separate the features and labels data into training and testing datasets.
-	Import the machine learning model from the library - in this instance, we will be importing LogisticRegression from SKLearn.
-	Instantiate the model.
-	Fit the model using the training data.
-	Use the model to make predictions using the features test data.
-	Evaluate the predictions - Evaluations are done by calculating and comparing metrics like accuracy score, a confusion matrix, and a classification report.
**Machine Learning Methods Used**
- Logistic Regression model from SKLearn
- train_test_split from SKLearn
- confustion_matrix from SKLearn
- classification_report from SKLearn

## Results

* Machine Learning Model - Logistic Regression:
  ** Accuracy Score:** 99%
  **Precision Score**: 
  Class 0 (Healthy Loans): 100%
  Class 1 (High Risk Loans): 85%
  **Recall Scores**: 
  Class 0 (Healthy Loans): 99%
  Class 1 (High Risk Loans): 91%
## Summary
The model does a solid job of using original data to predict the values of healthy loans. Precision was at 100% and recall at 99%.

As for high risk loan predictions, precision was 85% and recall was 91%, so not as precise as healthy loans.
