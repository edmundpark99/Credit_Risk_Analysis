# Credit_Risk_Analysis

**Overview**

This analysis employed machine learning to train the device to perform analysis on credit card risk. We employed the imbalanced-learn and scikit-learn libraries to create models that could study credit card risk. We then utilized six different algorithms: RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier, and EasyEnsembleClassifier. We oversampled the data using the first two algorithms, undersampled it using ClusterCentroids, did a combination of oversampling and undersampling using SMOTEENN, and then used the final two algorithms to compare models that help reduce bias in the data presented.

**Results**

*Naive Oversampling Model*

![Random Oversampling Model](https://user-images.githubusercontent.com/6594718/175841962-a5c09f8f-474d-49e6-8621-17ccc64b3a15.png)

- The balanced accuracy score of the Naive Oversampling Model is 64.4%
- The high risk precision score is 1% with a recall score of 61%
- The low risk precision score is 100% with a recall score of 68%

*SMOTE Oversampling Model*

![SMOTE Oversampling](https://user-images.githubusercontent.com/6594718/175842307-cf356475-e9c8-4ef3-8ff1-0fa2fcdc2548.png)

- The balanced accuracy of the SMOTE model is 63.7%
- The high risk precision score is 1% with a recall score of 64%
- The low risk precision score is 100% with a recall score of 63%

*Undersampling/ClusterCentroids Model*

![Undersampling Model](https://user-images.githubusercontent.com/6594718/175842499-3b7eed3c-52df-4a5d-afb4-518ad5689512.png)

- The balanced accuracy score of the ClusterCentroids Undersampling Model is 52.9%
- The high risk precision score is 1% with a recall score of 61%
- The low risk precision score is 100% with a recall score of 45%

*SMOTEENN/Mixed Sampling Model*

![SMOTEENN Model](https://user-images.githubusercontent.com/6594718/175842714-313f77ed-1770-4269-9f9e-957555c320f6.png)

- The balanced accuracy score of the SMOTEENN model is 62.4%
- The high risk precision score is 1% with a recall score of 71%
- The low risk precision score is 100% with a recall score of 54%

*Balanced Random Forest Classifier Model*

![BRFC Model](https://user-images.githubusercontent.com/6594718/175843057-9e1f2ab9-1fd6-4d0d-9f23-c718233491fc.png)

- The balanced accuracy score of the Balanced Random Forest Classifier Model is 78.8%
- The high risk precision score is 4% with a recall score of 67%
- The low risk precision score is 100% with a recall score of 91%

*EasyEnsembleClassifier Model*

![EEC Model](https://user-images.githubusercontent.com/6594718/175843319-978d82ac-d3bf-4d5c-b60f-c2a68d7e7f34.png)

- The balanced accuracy score of the EEC model is 92.5%
- The high risk precision score is 7% with a recall score of 91%
- The low risk precision score is 100% with a recall score of 94%

*Summary*

All in all, the balanced accuracy score varied from model to model, randing from 52.9% to 92.5%. The high risk precision score was always between 1% and 7% and the low risk always 100%. The recall score varied, but the best results came all from the EEC model, with a balanced accuracy score of 92.5%, high recall scores of 91% and 94% respectively, and precision scores being the highest of all with the high risk precision score being 7%. Thus, the EasyEnsembleClassifier Model is the best model to use. I would not recommend the ClusterCentroids model as it has the lowest balanced accuracy score as well as the lowest recall scores of all the models.
