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

### SMOTE Oversampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 62%
  - Recall Low Risk: 65%

### Cluster Centroid Undersampling
  - Accuracy Score: 63.6%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 59%
  - Recall Low Risk: 44%

### SMOTEENN Sampling
  - Accuracy Score: 51.2%
  - Precision High Risk: 1%
  - Precision Low Risk: 100%
  - Recall High Risk: 70%
  - Recall Low Risk: 57%

### Balanced Random Forest Classifying
  - Accuracy Score: 88.8%
  - Precision High Risk: 3%
  - Precision Low Risk: 100%
  - Recall High Risk: 68%
  - Recall Low Risk: 89%

### Easy Ensemble Classifying
  - Accuracy Score: 91.9%
  - Precision High Risk: 7%
  - Precision Low Risk: 100%
  - Recall High Risk: 90%
  - Recall Low Risk: 94%

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
