# credit_risk_classification
Amanda Baynard

### Split the Data into Training and Testing Sets

### Create Logistic Regression Model with Organic Data

### Credit Analysis Report

Using buleted lists, describe the balanced accuracy scores and the precision and recall of all machine learning models.

* Machine Learning Model 1:
    * Accuracy: 94.5%
    * Precision:
        * Healthy Loans: 100%
        * High Risk Loans: 87%
        
    * Recall:
        * Healthy Loans: 100%
        * High Risk Loans: 90%

* Machine Learning Model 2:
    * Accuracy: 99.2%
    * Precision:
        * Healthy Loans: 100%
        * High Risk Loans: 86%
        
    * Recall:
        * Healthy Loans: 99%
        * High Risk Loans: 99%
        
Both models perform very strongly when predicting healthy loans. With the second model, using the resampled data, accuracy and recall greatly improved to nearly perfect scores. Precision remains an issue with both models, staying at 87%.
The recommendation is to use Model 2. The model using resampled data as showed an overall increase in accuracy at detecting high-risk loan.
Since both models correctly predict healthy loans, it is more prudent to have a model that correctly classifies more high-risk loans, even. The risk associated with misclassifying a healthy loan as high-risk is lower than the risk of not classifying a high-risk loan as such.
