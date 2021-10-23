# Credit_Risk_Analysis

--------------------------------------

## **Overview**

--------------------------------------

- Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

--------------------------------------

## **Results**

--------------------------------------

- ## **Naive Random Oversampling**
![Naive%20Random%20Oversampling.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/Naive%20Random%20Oversampling.PNG)


- ## **SMOTE Oversampling**
![SMOTE%20Oversampling.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/SMOTE%20Oversampling.PNG)


- ## **Undersampling**
![Undersampling.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/Undersampling.PNG)


- ## **Combination (Over and Under) Sampling**
![Combination%20(Over%20and%20Under)%20Sampling.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/Combination%20(Over%20and%20Under)%20Sampling.PNG)


- ## **Balanced Random Forest Classifier**

![Balanced%20Random%20Forest%20Classifier.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/Balanced%20Random%20Forest%20Classifier.PNG)

- ## **Easy Ensemble AdaBoost Classifier**

![Easy%20Ensemble%20AdaBoost%20Classifier.PNG](https://github.com/Bionicbabes/Credit_Risk_Analysis/blob/main/Re/Easy%20Ensemble%20AdaBoost%20Classifier.PNG)


--------------------------------------

## **Summary**

--------------------------------------

- The easy ensemble adaboost classifier renders the best results when comparing all the techniques used in the above analysis.  With an overall calculated balance accuracy score of 93& this is a unique identifier taking into consideration the precision and recall that is indicative that we should be using this analysis.  From looking at the results of all the analaysis this is the recommend modeling that I would use moving forward.  This by no means suggest that there will be no mistakes by this results and there will still be a need for a underwriter to verify all bank statements and formal loan documentation such as proof of employement, credit checks etc. 
