# Supervised Classification — Titanic

A hands-on Machine Learning project where I applied different **Supervised Classification algorithms** on the Titanic dataset.

The goal of this project was to understand how different classification models learn from the same dataset and predict whether a passenger survived.

## Dataset

The project uses the **Titanic dataset**, where the target variable is:

- `Survived = 0` → Did not survive
- `Survived = 1` → Survived

## What I Covered

### Data Preparation
- Data cleaning
- Exploratory Data Analysis (EDA)
- Handling missing values
- Encoding categorical features
- Feature scaling
- Train-test split

### Classification Models

The models implemented in the project are:

- Logistic Regression
- K-Nearest Neighbors (KNN)
- Naive Bayes
- Decision Tree
- Support Vector Machine (SVM)

All models are implemented and compared in **one notebook/file** using the same dataset and preprocessing workflow.

## Model Evaluation

The models are evaluated using classification metrics such as:

- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix

This helps understand how well each model performs and how their predictions differ.

## Workflow

```text
Titanic Dataset
      ↓
EDA
      ↓
Data Cleaning
      ↓
Preprocessing
      ↓
Train-Test Split
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
