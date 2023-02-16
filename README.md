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

### Recall Rate for High Risk
This analysis is looking to find the best model to use to detect if a loan is high risk. We are looking for the model that allows the least amount of high risk loans pass though undetected as a false negative. The statistic we will use to measure this is the Recall rate for high risk. As you can see below, EasyEnsemble Classifying, SMOTEENN Sampling and Balanced Random Forest Classifying had the highest recall rates.

| Method/Measure                    | Recall |
|-----------------------------------|--------|
| Naive Random Oversampling         | 62%    |
| SMOTE Oversampling                | 62%    |
| Cluster Centroid Undersampling    | 59%    |
| SMOTEENN Sampling                 | 70%    |
| Balanced Random Forest Classifying| 68%    |
| Easy Ensemble Classifying         | 90%    |


### Recall Rate for Low Risk
The next important sttistic we can look at is the recall rate for low risk. This shows how many low risk loans are predicted to be high risk. 
The 2 highest Low Risk Recall rates were Easy Ensemble Classifying and Balanced Random Forest Classifying.

| Method/Measure                    | Recall |
|-----------------------------------|--------|
| Naive Random Oversampling         | 69%    |
| SMOTE Oversampling                | 65%    |
| Cluster Centroid Undersampling    | 44%    |
| SMOTEENN Sampling                 | 57%    |
| Balanced Random Forest Classifying| 89%    |
| Easy Ensemble Classifying         | 94%    |

### Accuracy
The accuracy score shows how well the model performs overall.
The highest accuracy rates, by a large margin are once again, Easy Ensemble Classifying and Balanced Random Forest Classifying.

| Method/Measure                    |Accuracy   |
|-----------------------------------|-----------|
| Naive Random Oversampling         | 65.4%     |
| SMOTE Oversampling                | 63.6%     |
| Cluster Centroid Undersampling    | 63.6%     |
| SMOTEENN Sampling                 | 51.2%     |
| Balanced Random Forest Classifying| 88.8%     |
| Easy Ensemble Classifying         | 91.9%     |

## Recommendations
After factoring in all of the statistical variables of each Method, I would recommend using the Easy Ensemble Classifying Method for the mot accurate results. 
