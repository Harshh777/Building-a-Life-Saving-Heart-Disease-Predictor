# AI in Healthcare: Heart Disease Prediction System

## Project Overview
This project focuses on building a machine learning–based **heart disease prediction system** using clinical and demographic patient data.  
The goal is to analyze healthcare data, perform complete exploratory data analysis (EDA), manually preprocess features, and train multiple classification models to predict the presence of heart disease.

The project emphasizes **interpretability, correctness, and healthcare relevance**, making it suitable for academic evaluation and healthcare analytics portfolios.

---

## Problem Statement
Heart disease is one of the leading causes of mortality worldwide. Early detection using data-driven models can support clinicians in identifying high-risk patients and improving decision-making.

This project aims to:
- Understand patient data through detailed EDA
- Identify key medical factors related to heart disease
- Train and evaluate multiple machine learning models
- Compare model performance using appropriate classification metrics

---

## Dataset Description
The dataset contains patient-level clinical attributes such as:
- Demographic information (age, sex)
- Clinical measurements (blood pressure, cholesterol, heart rate)
- Diagnostic indicators (chest pain type, ECG results, exercise-induced angina)

### Target Variable
- `target = 1` → Presence of heart disease  
- `target = 0` → No heart disease  

---

## Exploratory Data Analysis (EDA)
The following EDA steps were performed:
- Dataset structure and data type inspection
- Missing value analysis
- Statistical summary of numerical features
- Target variable distribution analysis
- Univariate analysis (histograms, boxplots)
- Bivariate analysis (feature vs target)
- Correlation analysis and heatmaps
- Medical interpretation of key risk factors

EDA helped identify clinically meaningful relationships between features and heart disease.

---

## Data Preprocessing (Without Pipelines)
To demonstrate full understanding of preprocessing steps, **no Scikit-Learn Pipelines were used**.

Manual preprocessing included:
- Train–test split with stratification
- Missing value imputation
  - Numerical features: median
  - Categorical features: most frequent
- One-hot encoding of categorical variables
- Feature scaling using StandardScaler
- Alignment of train and test feature spaces

---

## Models Trained
The following classification models were trained and evaluated:

1. Logistic Regression (baseline, interpretable)
2. Random Forest Classifier
3. Support Vector Machine (SVM)
4. K-Nearest Neighbors (KNN)

Each model was trained independently using the manually preprocessed data.

---

## Model Evaluation
Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix

Special attention was given to **recall for the positive class (heart disease)**, as false negatives are critical in healthcare applications.

---

## Key Results
- Ensemble and kernel-based models showed improved performance over baseline
- Certain clinical features consistently demonstrated strong association with heart disease
- The dataset proved suitable for predictive modeling with proper preprocessing

---

## Tools & Technologies
- Python
- Google Colab
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-Learn


## Author
Harsh Raj
