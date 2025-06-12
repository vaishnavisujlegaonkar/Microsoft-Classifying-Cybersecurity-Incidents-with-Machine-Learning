# Microsoft-Classifying-Cybersecurity-Incidents-with-Machine-Learning



Project Overview
This project simulates a real-world data science scenario at Microsoft, where you're tasked with enhancing the effectiveness of Security Operation Centers (SOCs). The goal is to develop a machine learning classification model that can predict the triage grade of cybersecurity incidents using the comprehensive GUIDE dataset. The model classifies incidents as:

True Positive (TP)

Benign Positive (BP)

False Positive (FP)

The resulting system is intended to support guided response tools in prioritizing and triaging security alerts.

Skills Gained
Data Preprocessing & Feature Engineering

Machine Learning Classification (Logistic Regression, Decision Trees, Random Forest, XGBoost)

Model Evaluation (Macro-F1, Precision, Recall)

Handling Imbalanced Datasets

Hyperparameter Tuning & Cross-Validation

Feature Importance Analysis

 Project Approach
1.  Data Exploration
Inspected structure, variable types, and class distribution

Performed EDA using visualizations to understand trends and imbalances

2.  Data Preprocessing
Handled missing values

Applied feature engineering and transformations (e.g., datetime features)

Encoded categorical features using One-Hot, Label, or Target Encoding

3.  Data Splitting
Stratified train-validation split (80-20) to maintain class distribution

Prepared a clean test.csv dataset for final evaluation

4.  Model Development
Started with baseline models: Logistic Regression, Decision Tree

Trained advanced models: Random Forest, XGBoost

Used class_weight='balanced' and stratified splits to handle class imbalance

Performed RandomizedSearchCV for hyperparameter tuning

5.  Model Evaluation
Evaluated models using:

Macro-F1 Score

Precision

Recall

Compared final model performance against baseline

6.  Feature Importance & Interpretation
Computed Permutation Importance for feature insights

Identified top 20 influential features

Performed error analysis to identify common misclassifications

7.  Final Evaluation
Final model trained using best parameters from tuning

Evaluated on the full test dataset

Achieved significant improvement over baseline metrics

📊 Results
Final Model: Tuned Random Forest Classifier with class_weight='balanced'

Evaluation Metrics on Test Data

Model successfully reduced false positives and improved classification of TP/BP/FP

