# Credit_Risk_Analysis
## Overview of Project
Jill asks you to use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling to apply machine learning to solve a real-world challenge: credit card risk.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the `RandomOverSampler` and `SMOTE` algorithms, and undersample the data using the `ClusterCentroids` algorithm. Then, you’ll use a combinatorial approach of over and undersampling using the `SMOTEENN` algorithm. Next, you’ll compare two new machine learning models that reduce bias, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier`, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

* Data Source: ` Module-17-Challenge-Resources.zip` and `LoanStats_2019Q1.csv`
* Data Tools:  `credit_risk_resampling_starter_code.ipynb` and `credit_risk_ensemble_starter_code.ipynb`.
* Software: `Python 3.9`, `Visual Studio Code 1.50.0`, `Anaconda 4.8.5`, `Jupyter Notebook 6.1.4` and `Pandas`

# Deliverable 1:  
## Use Resampling Models to Predict Credit Risk
#### Deliverable 1 Requirements

For all three algorithms, the following have been completed:
- An accuracy score for the model is calculated
- A confusion matrix has been generated
- An imbalanced classification report has been generated 

# Deliverable 2:  
## Use the SMOTEENN algorithm to Predict Credit Risk 
### Deliverable Requirements:
The combinatorial SMOTEENN algorithm does the following:
- An accuracy score for the model is calculated
- A confusion matrix has been generated
- An imbalanced classification report has been generated  


# Deliverable 3:  
## Use Ensemble Classifiers to Predict Credit Risk 
### Deliverable Requirements:
#### Deliverable 3 Requirements

The `BalancedRandomForestClassifier` algorithm does the following:
- An accuracy score for the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated 
- The features are sorted in descending order by feature importance

The `EasyEnsembleClassifier` algorithm does the following:
- An accuracy score of the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated  

### DELIVERABLE RESULTS:
**SMOTEENN:**  
![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r4.png)

**SMOTE:**  
![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r2.png)

**RandomOverSample:**  
![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r1.png)

**ClusterCentroids:**  
![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r3.png)

**EasyEnsembleClassifier:**  
![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r6.png)


**BalancedRandomForestClassifier:**


![d1](https://github.com/SLCunningham21/Credit_Risk_Analysis/blob/main/resources/Images/r5.png)

## SUMMARY

For all models, utlizing **EasyEnsembleClassifier** is the most effective because it provides the highest Score for all risk loans.
The precision is low or none for all the models. In General, above the 90% of the current analysis, utlizing **EasyEnsembleClassifier** will perform a High-Risk loan precision as a great value for the overall analysis. 


