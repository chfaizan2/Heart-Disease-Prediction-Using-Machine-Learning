# Heart-Disease-Prediction-Using-Machine-Learning
## DeveloperHub Corporation Internship Task 2
### Task Objective
Develop a heart disease prediction system using machine learning models to classify patients as having heart disease or not based on medical features, following a complete data science workflow from preprocessing to model evaluation.

### Dataset Used
File: HeartDiseaseTrain-Test.csv

Size: 1,025 rows × 14 columns initially, 302 rows after removing 723 duplicates

Features: 13 medical/demographic features including age, sex, chest pain type, blood pressure, cholesterol, etc.

Target: target (0 = no heart disease, 1 = heart disease)

### Models Applied
Logistic Regression (linear classifier)

Decision Tree Classifier (non-linear tree-based model)

### Key Results and Findings
Data Quality: No missing values; 723 duplicates removed

Class Balance: Original slight imbalance (51.3% disease vs 48.7% no disease) corrected using SMOTE

Preprocessing: Numerical features scaled (MinMaxScaler), categorical features label-encoded

Visual Insights: Males, asymptomatic chest pain, higher age, and lower max heart rate correlate with heart disease

Model Evaluation: Both models evaluated using accuracy, precision, recall, F1-score, confusion matrices, and ROC curves

Feature Importance: Identified most predictive features for both linear (coefficients) and tree-based (split importance) models

Complete Pipeline: End-to-end workflow from data loading through preprocessing, visualization, modeling, and evaluation
