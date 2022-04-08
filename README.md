# Credit Risk Analysis

## Overview of Project
Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use `imbalanced-learn` and `scikit-learn` libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the `RandomOverSampler` and `SMOTE` algorithms, and undersample the data using the `ClusterCentroids` algorithm. Then, you’ll use a combinatorial approach of over and undersampling using the `SMOTEENN` algorithm. Next, you’ll compare two new machine learning models that reduce bias, `BalancedRandomForestClassifier` and `EasyEnsembleClassifier`, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

### DELIVERABLE RESULTS:
Below are the results from the various techniques used to predictive model for High-Risk loans.  

**SMOTEENN:**  

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/smoteen.png)
          

**SMOTE:**  

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/smote.png)

**RandomOverSample:**  

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/RandomOverSample.png)

**ClusterCentroids:**  

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/ClusterCentroids.png)

**EasyEnsembleClassifier:**  

The `EasyEnsembleClassifier` algorithm does the following:
- An accuracy score of the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/eec.png)


**BalancedRandomForestClassifier:**

The `BalancedRandomForestClassifier` algorithm does the following:
- An accuracy score for the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated 
- The features are sorted in descending order by feature importance

![d1](https://github.com/Abrannstrom/Supervised_MachineLearning/blob/main/brfc.png)

## SUMMARY

For all models, utlizing EasyEnsembleClassifier is the most effective beacuse it provides a highest scores for all Risk loans.
The precision is low or none for all of the other high-risk models. In General, above the 90% of the current analysis, utlizing **EasyEnsembleClassifier** will perform a High-Risk loan precision as a great value for the overall analysis. 
