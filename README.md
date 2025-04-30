# EEG-Based Epilepsy Detection using Machine Learning

##  Project Overview
This project is submitted for the MATH516: *Machine Learning and Artificial Intelligence for Healthcare* module, MSc Health Data Science and Statistics at  University of Plymouth (2025).

The objective is to classify subjects into epileptic and non-epileptic groups based on EEG features using both classical machine learning and deep learning models.

##  Repository Structure

- `notebooks/`: Contains the final Jupyter Notebook (`eeg_epilepsy_detection_ml.ipynb`)
- `plots/`: Saved plots (ROC curves, feature importance charts, heatmaps, etc.)
- `data/`: Dataset (`Epileptic_featured_data.csv`)

##  Tools and Libraries Used

- Python 3.11
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn
- tensorflow / keras

##  Models Developed

- Logistic Regression
- Random Forest Classifier
- Support Vector Machine (SVM)
- K-Nearest Neighbors (KNN)
- Deep Learning Neural Network (MLP)

##  Evaluation Metrics

- Accuracy
- Sensitivity (Recall)
- Specificity
- Precision
- F1-Score
- AUC (Area Under the ROC Curve)

##  Key Highlights

- Data preprocessing, feature scaling and normalization
- Exploratory Data Analysis (EDA)
- Feature selection and importance analysis (Random Forest, RFE, Embedded methods)
- Fold change analysis between epileptic and non-epileptic subjects
- ROC curve comparisons between ML and Deep Learning models
- Performance evaluation and model comparison
