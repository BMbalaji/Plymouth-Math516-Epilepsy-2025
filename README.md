# EEG-Based Epilepsy Detection using Machine Learning

This repository contains the full implementation of a machine learning pipeline developed for EEG-based epilepsy detection. The work was conducted as part of the MSc Health Data Science and Statistics program at the University of Plymouth for the MATH516 module: *Machine Learning and Artificial Intelligence for Healthcare* (2025).

 **All data processing, analysis, modelling, and visualizations were implemented entirely in Python.**


##  Project Overview

The aim is to classify subjects as *epileptic* or *non-epileptic* based on engineered EEG features using both classical machine learning and deep learning techniques.

The pipeline includes:
- Data cleaning and standardization
- Exploratory Data Analysis (EDA)
- Multiple feature selection strategies
- Training of classical ML models (Logistic Regression, Random Forest, SVM, KNN)
- Deep learning with a Multi-Layer Perceptron (Keras)
- Model evaluation and visualization

##  Models Implemented

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)  
- K-Nearest Neighbors (KNN)  
- Deep Neural Network (Keras)

##  Evaluation Metrics

- Accuracy  
- Precision, Recall (Sensitivity), Specificity  
- F1 Score  
- Area Under the Curve (AUC)  
- ROC Curves & Confusion Matrices

##  Key Highlights

- Balanced dataset (198 samples, 99 per class)
- 40 EEG-derived features across Delta, Theta, Alpha, Beta, Gamma bands
- Fold-change analysis and correlation heatmaps
- Feature selection using:
  - Random Forest importance
  - Recursive Feature Elimination (RFE)
  - Permutation Importance
  - Correlation-based ranking
- Minimal feature set with comparable performance (AUC > 0.85)

##  Results Summary

| Model                  | Accuracy | F1 Score | AUC  |
|------------------------|----------|----------|------|
| Random Forest          | 100%     | 1.00     | 1.00 |
| Support Vector Machine | 100%     | 1.00     | 1.00 |
| Logistic Regression    | 97.5%    | 0.97     | 1.00 |
| K-Nearest Neighbors    | 95.0%    | 0.95     | 0.99 |
| Deep Learning (MLP)    | 98.0%    | 0.97     | 1.00 |


## Conclusion

This project successfully demonstrates that combining engineered EEG features with classical machine learning and deep learning models can deliver highly accurate, interpretable, and scalable solutions for epilepsy detection.

