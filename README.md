# Credit_Risk_Analysis

## Objective 
The purpose was to utilize credit card data and perform machine learning to determine balanced random forest classifier and easy ensemble classifier, to predict credit risk.

## Results

### Naive Random Oversampling
  - Accuracy Score: 65.4%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 62%
  - Recall Low Risk: 69%
  
![acc score](https://user-images.githubusercontent.com/113067853/219502881-49a77699-16c3-403b-a6bf-b9b5b2750c8b.PNG)
![imbalance class](https://user-images.githubusercontent.com/113067853/219502900-680e9b1c-3dca-467a-8e4f-7a10615063e3.PNG)

### SMOTE Oversampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 62%
  - Recall Low Risk: 65%

![over acc score](https://user-images.githubusercontent.com/113067853/219503155-3117449c-ebd7-4df1-88dc-4bfba84fac2c.PNG)
![over imbala](https://user-images.githubusercontent.com/113067853/219503166-67c3236b-563b-4bd6-aef8-02273a00fe71.PNG)

### Cluster Centroid Undersampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 59%
  - Recall Low Risk: 44%

![over acc score](https://user-images.githubusercontent.com/113067853/219506199-ed187be8-83f0-44bf-91cb-b615860e86f1.PNG)
![over imbala](https://user-images.githubusercontent.com/113067853/219506203-45162cae-e20d-4003-a563-b2de9ae46460.PNG)

### SMOTEENN Sampling
  - Accuracy Score: 51.2%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 70%
  - Recall Low Risk: 57%
 
![Capture1](https://user-images.githubusercontent.com/113067853/219504889-a5c50bcd-3908-455b-89fa-053ba4711abf.PNG)
![Capture2](https://user-images.githubusercontent.com/113067853/219504917-4a9e3749-b779-46ba-ab95-7ce2b2ba8ce2.PNG)

### Balanced Random Forest Classifying
  - Accuracy Score: 88.8%
  - Precision High Risk: 3%
  - Precision Low Risk: 100%
  - Recall High Risk: 68%
  - Recall Low Risk: 89%
  
![balforest acc score](https://user-images.githubusercontent.com/113067853/219503994-f58bf9df-b5ba-400a-b9d4-b64dbe51360f.PNG)
![balforestclass](https://user-images.githubusercontent.com/113067853/219504002-5fabb9b5-e817-4b1f-98cd-203e113fd05e.PNG)


### Easy Ensemble Classifying
  - Accuracy Score: 91.9%
  - Precision High Risk: 7%
  - Precision Low Risk: 100%
  - Recall High Risk: 90%
  - Recall Low Risk: 94%
 
![easyforest acc score](https://user-images.githubusercontent.com/113067853/219503756-1c6638c6-6682-423c-9e6b-93e5292128f8.PNG)
![easyforest class](https://user-images.githubusercontent.com/113067853/219503762-4873ae57-4638-4833-8240-556ceff7ac49.PNG)

## Summary

The analysis of the data was to find the best model to predict credit risk of the given data. After reviewing the data above I would recommend Easy Ensemble Classifying Method as it was the most accurate with a recall high risk of 90% and a low risk of 94%. This was the best of all the methods used. 
