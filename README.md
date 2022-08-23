# Prediction of outflow of bank customers

Beta Bank customers are leaving: little by little, chipping away every month. 
The bankers figured out it’s cheaper to save the existing customers rather than to attract new ones. 
We need to predict whether a customer will leave the bank soon.

## Task Statement.
Predict if a customer will leave the bankPredict if a customer will leave the bank.

##  The goal.
- Build a model with the maximum possible F1 score. 
- The F1 score should be at least 0.59. 
- Check the F1 value for the test set.
- Measure the AUC-ROC metric.
- Compare the AUC-ROC metric with the F1 metric.

## Data description.

Data on the behavior of customers and cancellation of contracts with the bank are presented.

https://www.kaggle.com/barelydedicated/bank-customer-churn-modeling

## Conclusion
The model of a Random Forest with hyperparameters showed itself best of all: number of trees = 60, depth = 10, 
which was trained on data balanced by the upsampling technique.

In the test sample, this model showed the results: F1 = 0.64 and AUC-ROC = 0.86.
