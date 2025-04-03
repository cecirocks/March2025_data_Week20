# Module 20 Report

## Overview of the Analysis


The goal of this project is to train a machine learning model using lending data to assess credit card loan risk. The model should be flexible, allowing for easy testing of various machine learning algorithms, and should present results in a way that facilitates quick comparison and accuracy evaluation to identof the creditworthiness of borrowers. To streamline the process of testing multiple models on the same dataset, I used several formulas. As per the project requirements, I implemented a Logistic Regression model, and additionally tested the data using a KNN model, a Random Forest model and a XGBOOST model for comparison.

## Results

* Logistic Regreession Model
    * Accuracy Score: The model demonstrates a 99% accuracy, with no signs of overfitting
    * Precision Score: The precision score indicates that the model is more accurate in predicting healthy loans than high-risk loans despite being imbalance 
    * Recall Score: has a 98% recall score
      
* KNN model
    * Accuracy Score: Has a 99% accuracy, but has signs of overfitting and is slow and data is large
    * Precision Score: The precision score indicates that the model has some difficulty accurately predicting high-risk loans, resulting in false positives
    * Recall Score: has a 99% recall score

* Random Forest model
    * Accuracy Score: This model has a 99% accuracy and has a bit of overfitting
    * Precision Score: The precision score indicates good at correctly identifying healthy loans but struggles a bit more in predicting high-risk loans correctly
    * Recall Score: has a 89% recall score
            
* XGBOOST model
    * Accuracy Score: The model has 99% accuracy, with no overfitting
    * Precision Score: The precision score indicates that the model is more accurate in predicting healthy loans than high-risk loans but tends to misclassify some healthy loans as high-risk
    * Recall Score: has a 99% recall score
          
## Summary

* The Logistic model appears to be a strong classifier overall, with high accuracy, precision, and recall, especially for healthy loans. However, there is room for improvement in the precision of high-risk loan predictions. This could be addressed by tuning the model or trying different algorithms or balancing techniques to improve the performance high-risk loans. Out of all the models the LGBM model generalizes better but the XGBOOST has the best metrics.

