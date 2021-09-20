# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

The Purpose of this analysis was to use customer information to determine credit worthyness for a peer to peer lending company

The data that was looked as was information about the loan and the borrower, such as the size of their loan, the interest rate of that loan, their income, debt to income ratio, how many accounts they have, and if they have any derogitory marks. There is also a data column called loan status which is a binary 0 for a healthy loan or 1 for an unhealthy loan

The 0 loans numbered 75036 while the 1 numbered 2500

We preformed a split of the customer data into variable X and the binary loan status into variable y 

We then used test_train_split to put the data into a form where we can perform linear regression on it using sklearn

After fitting the model and using the predict function we managed to get a a classification model that worked pretty well

In an effort to improve this the data was oversampled as there was very little 1 data as compared to 0 data

After oversampling we performed the same operations 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
  
  * Accuracy  0.9218124642767772

  * Precision 
      - 0 1.00 
      - 1 0.85
  * Recall 
      - 0 0.99
      - 1 0.91



* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
  * Accuracy 0.9205494133884273
  
  * Precision 
      - 0 0.99
      - 1 0.99
  * Recall 
      - 0 1.00
      - 1 0.84


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* The oversampled model was slighly less accurate in terms of balanced accuracy score, but I believe it to be slightly more accurate due to an overall lower spread between the precision and recall values of the 0 and 1
* It is definitely more important to properly identify the 1 as they represent the unhealthy loans

If you do not recommend any of the models, please justify your reasoning.
