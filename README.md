# Credit_Risk_Analysis
## Overview
The purpose of this project is to build different machine learning models to predict customer credit risk.

## Results
### Random Oversampling

![Random Oversampling](https://user-images.githubusercontent.com/116690861/225007342-c666a4ca-1305-461b-9311-2689718834f4.png)

- The balanced accuracy score is 63%
- The precision for for high risk is low (1%) and for low risk is high (100%)
- The recall for high risk is 66% and for low risk is 65%

### SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/116690861/225009089-4bef3f77-1acc-41f5-9d2f-7447c4108715.png)

- The balanced accuracy score is 63%
- The precision for for high risk is low (1%) and for low risk is high (100%)
- The recall for high risk is 62% and for low risk is 64%

### Clustercentroids

![Undersampling](https://user-images.githubusercontent.com/116690861/225009816-dc83e8ba-f80a-4ca0-a53c-8aa687d9dfbf.png)

- The balanced accuracy score is 51%
- The precision for for high risk is low (1%) and for low risk is high (100%)
- The recall for high risk is 59% and for low risk is 43%

### SMOTEENN

![SMOTEENN](https://user-images.githubusercontent.com/116690861/225010360-c63f64d1-4b54-4174-97db-ae007d179687.png)

- The balanced accuracy score is 62%
- The precision for for high risk is low (1%) and for low risk is high (100%)
- The recall for high risk is 71% and for low risk is 54%

### Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/116690861/225012069-f3043347-5f5d-4e8b-b36d-2f0cba5624ea.png)

- The balanced accuracy score is 78%
- The precision for for high risk is low (4%) and for low risk is high (100%)
- The recall for high risk is 67% and for low risk is 91%

### Easy Ensemble Classifier

![Easy Ensemble Classifier](https://user-images.githubusercontent.com/116690861/225012829-9f3330f5-fd02-4df5-a935-5a648374f436.png)

- The balanced accuracy score is 92%
- The precision for for high risk is low (7%) and for low risk is high (100%)
- The recall for high risk is 91% and for low risk is 94%

## Summary

After reviewing the scores of all six machine learning models used the Easy Ensemble Classifier had the highest accuracy score. However, I would not recommend using any of these models for this particular project as all of them showed weak precision when predicting high risk. This means that none of the models used could accurately predict who the high risk borrowers would be.  
