<p align="center">
  <img src="https://github.com/CosimoFaeti/human-activity-recognition-analysis/assets/99746565/df0113e1-ea92-4dd2-a4b4-6f126b74a65e" alt="unipi" width="30%">
</p>

# Human Activity Recognition Analysis  
This repository contains my project for the *Data Mining II course* of my Master's degree in Data Science and Business Informatics at Università di Pisa.
The aim of the project is to conduct a comprehensive analysis and comparison of different machine learning models on 
*Human Activity Recognition using Smartphones* data set. Specifically, it concerns experiments that have been carried out
with a group of 30 volunteers. Each person performed six activities (WALKING, WALKING UPSTAIRS,
WALKING DOWNSTAIRS, SITTING, STANDING, LAYING) wearing a smartphone on the waist. Using
the embedded accelerometer and gyroscope of the smartphone were captured 3-axial linear acceleration and
3-axial angular velocity.

## Repository Overview
In this repository, in the root level, you can find the pdf version of the report, the data and the code for the implementation of machine learning models for Human Activity Recognition data set. More specifically:

**Exploratory Analysis and Data Cleaning**:
* Module1_Point1_DataUnderstading_DataPreparation.ipynb : contains data understanding, preparation and cleaning, as well as exploratory data analysis

**Simple Classification and Imbalanced Learning**:
* Module1_Point2_DecisionTree_KNN_MULTICLASS.ipynb : contains the implementation of Decision Tree and K-NN on two classification tasks (multiclass and binary classification problem)
* Module1_Point4_ImbalanceLearning.ipynb : contains the implementation of balancing techniques (Random Undersampling, Random Oversampling, SMOTE)

**Outlier Detection**:
* Module1_Point3_Outlier_Detection.ipynb : contains the implementation of outlier detection models (Angle-Based Outlier Degree, Isolation Forest, Local Outlier Factor)

**Dimensionality Reduction**:
* Module1_Point5_DimensionalityReduction.ipynb : contains the implementation of dimensionality reduction techniques (Gaussian Random Projection, Principal component analysis (PCA), IsoMap)

**Advanced Classification Methods**:
* Module2_Point1_AdvancedClassification.ipynb : contains the implementation of advanced classification methods (Naive Bayes, Linear Regression, Logistic Regression, Support Vector Machine, Neural Networks, Ensemble classifier (Random Forest, Bagging, AdaBoost), Gradient Boosting)

**Time Series Analysis**:
* Module3_Time_Series_Analysis.ipynb : contains the implementation of time series analysis (Clustering, Motifs and Anomalies discovery, classification)

**Sequential Pattern Mining and Advanced Clustering**:
* Module4_Sequential_Patterns_and_Advanced_Clustering.ipynb : contains implementation of sequential pattern mining and advanced clustering models (X-Means, OPTICS)

**Explainability**:
* Module5_Explainability.ipynb : contains implementation of explainability techniques (SHAP, LIME)

