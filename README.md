# Credit Risk Analysis

## Overview
For this analysis, we were given credit card risk data. We were expected to analyze two categories of supervised machine learning modules - resampling an ensemble. In total, we created six models (4 resampling, 2 ensemble) and compared the accuracy score and imbalanced classification report to determine which is recommended.

## Results

### Resampling Models

##### Naive Random Oversampling
 - Balanced Accuracy Score: 65.81%
 - Precision/Recall Score: 
 ![image](https://user-images.githubusercontent.com/41657419/229363146-fc122dc5-b4af-4c54-9955-55219c9e3832.png)
 
##### SMOTE Oversampling
 - Balanced Accuracy Score: 66.14%
 - Precision/Recall Score: 
![image](https://user-images.githubusercontent.com/41657419/229363236-62194236-7fbe-4f5e-94fd-2aa0b20e715e.png)

##### Undersampling
 - Balanced Accuracy Score: 66.14%
 - Precision/Recall Score: 
![image](https://user-images.githubusercontent.com/41657419/229363259-2f1377cc-08dd-4e2e-8b14-a55207f7ff58.png)

##### Combination (Over and Under) Sampling
 - Balanced Accuracy Score: 54.47%
 - Precision/Recall Score: 
![image](https://user-images.githubusercontent.com/41657419/229363313-3bea825d-ab8b-444e-a7a6-db974c2b9e1a.png)

### Ensemble Models

##### Balanced Random Forest Classifier
 - Balanced Accuracy Score: 75.43%
 - Precision/Recall Score: 
![image](https://user-images.githubusercontent.com/41657419/229363429-87366705-bd16-4044-9760-b44ea1995b33.png)

##### Easy Ensemble AdaBoost Classifier
 - Balanced Accuracy Score: 91.23%
 - Precision/Recall Score: 
![image](https://user-images.githubusercontent.com/41657419/229363462-d306c7bd-b028-451f-8dc4-adb317929822.png)

## Summary

Both of the ensemble models show much higher accuracy score compared to the resampling models, so I recommend ensemble. Between the two ensemble models, the Easy Ensemble AdaBoost Classifier models shows not only a higher accuracy score than the Balanced Random Forest Classifier, but also an improved precision and recall score. I recommend the Ensemble AdaBoost Classifier model be used for credit card risk data.
