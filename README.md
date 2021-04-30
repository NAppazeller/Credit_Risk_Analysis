# Credit Risk Analysis

## Overview: 

Fast Lending, a lending services company, has asked for assistance accessing credit risk. The project will include building and evaluating six machine learning models to predict credit risk. The models will also be evaluated for performance and ability to predict data. The guiding objective is to expedite the loan approval process and deliver clients with low default rates.

## Results: 

Accuracy score: validating a model's performance
Precision (predictive value:  measure of the likelihood.
Recall: assess a model's performance with sensitivity or determine the accuracy of the precision
F1 score (harmonic mean) can be characterized as a single summary statistic of precision and sensitivity

### Oversampling

* Balanced accuracy for the overampling method was 62.8%.
* High-risk precision and recall scores were 1.0% and 62%, respectively.
* Low-risk precision and recall scores were 100.0% and 68%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/Oversampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/Oversampling_classification_imbalance.jpg)

  
### SMOTE Oversampling 

* Balanced accuracy for the overampling method was 63.0%.
* High-risk precision and recall scores were 1.0% and 61%, respectively.
* Low-risk precision and recall scores were 100.0% and 65%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/SMOTE_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/SMOTE_classification_imbalance.jpg)

### Undersampling

* Balanced accuracy for the overampling method was 51.1%.
* High-risk precision and recall scores were 1.0% and 59%, respectively.
* Low-risk precision and recall scores were 100.0% and 44%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/Undersampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/Undersampling_classification_imbalance.jpg)

### Combination (Over and Under) Sampling

* Balanced accuracy for the overampling method was 61.7%.
* High-risk precision and recall scores were 1.0% and 70% respectively.
* Low-risk precision and recall scores were 100.0% and 53% respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/OverUnderSampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/OverUnderSampling_classification_imbalance.jpg)

### Balanced Random Forest Classifier

* Balanced accuracy for the overampling method was 78.8%.
* High-risk precision and recall scores were 4.0% and 67%, respectively.
* Low-risk precision and recall scores were 100.0% and 91%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/RandomForest_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/RandomForest_classification_imbalance.jpg)


### Easy Ensemble Classifier

* Balanced accuracy for the overampling method was 92.5%.
* High-risk precision and recall scores were 1.0% and 91%, respectively.
* Low-risk precision and recall scores were 100.0% and 94%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/EEC_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/EEC_classification_imbalance.jpg)

## Summary: 

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
