# credit-risk-classification
credit-risk-classification

## Overview of the Analysis

The purpose of this analysis was to see if models could predict healthy loans and high-risk loans accurately.  The models used data such as loan size, the borrower’s income, the debt-to-income ratio, the interest rate, the number of accounts the borrower has with the bank, the derogatory marks on the accounts and the total debt the borrow has. 
After reading the .csv file and creating a dataframe from it, it was necessary to separate out the Loan_Status column from the dataframe, as this is the column that stores the ‘0’ for healthy loan and the ‘1’ for high-risk loans.  By removing the Loan_Status data from the dataframe, we can then use different models on the remaining data columns to see how they predict the values of ‘0’ and ‘1’.
Then two dataframes were created.  Both of these new dataframes contained the same data but will be used for different reasons.  The first dataframe is the training data which is used to train the model.  The second dataframe is the testing data which is used for testing the model.
The Logistic Regression Model was used on the training data. This fitted data was then used to make predictions based on the test data. 
Finally a confusion matrix and classification report were created and printed in order to analyze how well the testing data was able to predict healthy loans and high-risk loans. The results are below. 

# Results
•	Precision:
    o	Healthy Loans (‘0’): 1.00
    o	High-Risk Loans (‘1’): 0.85

•	Recall:
    o	Healthy Loans (‘0’): 0.99
    o	High-Risk Loans (‘1’): 0.91

•	Accuracy: 99%

## Summary
The Logistic Regression Model was very accurate with predicting healthy loans (‘0’) and did very well predicting high-risk loans (‘1’). I would recommend using this model because it is nearly 100% accurate in its predictions.  
