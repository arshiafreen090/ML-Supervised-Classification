# Supervised Classification — Titanic & Heart Disease Prediction

A hands-on Machine Learning project where I applied different **Supervised Classification algorithms** on two datasets: **Titanic** and **Heart Disease**.

The goal of this project was to understand how different classification models learn from data and predict binary outcomes.

## Datasets

### Titanic
The target variable is:

- `Survived = 0` → Did not survive
- `Survived = 1` → Survived

### Heart Disease
The target variable is:

- `HeartDisease = 0` → No heart disease
- `HeartDisease = 1` → Heart disease

## What I Covered

### Data Preparation
- Data cleaning
- Exploratory Data Analysis (EDA)
- Handling missing values
- Encoding categorical features
- Feature scaling
- Train-test split
- Stratified train-test splitting

### Classification Models

The following models were implemented and compared:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

The models were trained and evaluated separately on both datasets.

## Model Evaluation

The models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

This helped me understand the performance and differences between various classification algorithms.

## Workflow

```text
Dataset
   ↓
EDA
   ↓
Data Cleaning
   ↓
Preprocessing
   ↓
Encoding & Scaling
   ↓
Stratified Train-Test Split
   ↓
   ├── Logistic Regression
   ├── KNN
   ├── Naive Bayes
   ├── Decision Tree
   └── SVM
          ↓
      Predictions
          ↓
       Evaluation
          ↓
     Model Comparison
