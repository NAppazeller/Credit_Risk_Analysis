# Credit Risk Analysis

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/Header_image.jpg)

## Overview: 

Fast Lending, a lending services company, has asked for assistance building and evaluating six machine learning models to predict credit risk. The models will also be evaluated for performance and ability to predict data. The guiding objective is to expedite the loan approval process and determine clients with low default rates.

## Results: 

### Oversampling

* Balanced accuracy for the oversampling method was 62.8%.
* High-risk precision and recall scores were 1.0% and 62%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/Oversampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/Oversampling_classification_imbalance.jpg)

  
### SMOTE Oversampling 

* Balanced accuracy for the oversampling method was 63.0%.
* High-risk precision and recall scores were 1.0% and 61%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/SMOTE_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/SMOTE_classification_imbalance.jpg)

### Undersampling

* Balanced accuracy for the oversampling method was 51.1%.
* High-risk precision and recall scores were 1.0% and 59%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/Undersampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/Undersampling_classification_imbalance.jpg)

### Combination (Over and Under) Sampling

* Balanced accuracy for the oversampling method was 61.7%.
* High-risk precision and recall scores were 1.0% and 70% respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/OverUnderSampling_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/OverUnderSampling_classification_imbalance.jpg)

### Balanced Random Forest Classifier

* Balanced accuracy for the oversampling method was 78.8%.
* High-risk precision and recall scores were 4.0% and 67%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/RandomForest_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/RandomForest_classification_imbalance.jpg)


### Easy Ensemble Classifier

* Balanced accuracy for the oversampling method was 92.5%.
* High-risk precision and recall scores were 7.0% and 91%, respectively.

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/EEC_bal%20accuracy.jpg)

![](https://github.com/NAppazeller/Credit_Risk_Analysis/blob/main/photos/EEC_classification_imbalance.jpg)

## Summary: 

When referencing the F1 scores for the oversampling, SMOTE, undersampling and combination models it was clear there was a high level of imbalance between sensitivity and precision as demonstrated by the low scores. In comparison, the ensemble learners had materially higher balanced accuracy outcomes and modestly higher F1 scores. This would indicate a significant number of applicants were flagged as high-risk, but were likely low-risk. By erroneously rejecting potential clients the lender risks growing their client base and future profits. It would not be in the lenders best interest to use the current analysis models.
