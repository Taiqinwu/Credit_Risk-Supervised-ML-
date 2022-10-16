# Credit Risk Analysis

## Overview of the analysis
* Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

* Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

## Results:
* Below are the results from the six superived machine learning model:

### RandomOversampler
<img width="903" alt="image" src="https://user-images.githubusercontent.com/107168891/196060851-093e0339-6ef1-4fb4-a3d1-a4ba1002b9d8.png">

* Balanced Accuracy: 64%
* Precision: High-risk is 1% and for Low-risk is 100%
* Recall: High is 64% and Low is 65%

### SMOTE
<img width="1002" alt="image" src="https://user-images.githubusercontent.com/107168891/196060868-0e3b44c1-dd93-4e5b-a895-8bf0c6ecb7d3.png">

* Balanced Accuracy: 64%
* Precision: High-risk is 1% and for Low-risk is 100%
* Recall: High is 63% and Low is 66%

### ClusterCentroids
<img width="888" alt="image" src="https://user-images.githubusercontent.com/107168891/196061491-711e7467-ccdb-4178-bdf9-6ec7be6627f5.png">

* Balanced Accuracy: 53%
* Precision: High-risk is 1% and for Low-risk is 100%
* Recall: High is 61% and Low is 45%

### SMOTEENN
<img width="895" alt="image" src="https://user-images.githubusercontent.com/107168891/196061550-78236c25-8b91-4ab6-938c-62a49875d72b.png">

* Balanced Accuracy: 53%
* Precision: High-risk is 1% and for Low-risk is 100%
* Recall: High is 70% and Low is 57%

### Balanced Random Forest Classifier
<img width="900" alt="image" src="https://user-images.githubusercontent.com/107168891/196060964-1387e17e-a6e9-449c-b0ac-0efccf3dc2b4.png">

* Balanced Accuracy: 53%
* Precision: High-risk is 4% and for Low-risk is 100%
* Recall: High is 67% and Low is 91%

### Easy Ensemble AdaBoost Classifier
<img width="897" alt="image" src="https://user-images.githubusercontent.com/107168891/196060971-cf8fd813-fd19-4c5b-aedb-710f273c3190.png">

* Balanced Accuracy: 92%
* Precision: High-risk is 7% and for Low-risk is 100%
* Recall: High is 91% and Low is 94%

## Summary:
* Per analysis above we can see Easy Ensemble AdaBoost Classifier model have the highest score of 92%. Therefore, this model recommended since other model is lack of precision. 
