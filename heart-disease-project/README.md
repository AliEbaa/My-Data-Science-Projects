# Heart Disease Predictive Modeling Project

## Problem Statement

Can we predict the presence of heart disease using clinical measurements while prioritizing medical recall (sensitivity) to reduce false negatives?

---

## Dataset

- UCI Heart Disease Dataset (Cleveland)
- 303 patient records
- 13 clinical features
- Binary target (Heart Disease: Yes/No)

---

## Project Objectives

- Clean real-world medical data
- Perform exploratory data analysis
- Build interpretable predictive models
- Optimize recall for clinical safety
- Compare model feature importance
- Apply hyperparameter tuning

---

## Methodology

### 1. Data Cleaning
- Handled missing values
- Converted data types
- Replaced invalid entries

### 2. Exploratory Data Analysis
- Statistical summaries
- Correlation analysis
- Distribution analysis

### 3. Modeling
- Logistic Regression (interpretable baseline)
- Random Forest (nonlinear model)

### 4. Medical Optimization
- Class weighting
- Threshold tuning
- Recall-focused evaluation

### 5. Hyperparameter Tuning
- GridSearchCV
- Cross-validation

---

## Results

- Improved recall performance
- Reduced false negatives
- Identified clinically relevant features:
  - Chest pain type (cp)
  - Maximum heart rate (thalach)
  - ST depression (oldpeak)
  - Number of vessels (ca)

---

## Key Takeaways

- Clinical ML systems must prioritize sensitivity over raw accuracy.
- Threshold adjustment significantly affects patient risk.
- Feature importance comparison enhances interpretability.

---

## How to Run

1. Open the Jupyter Notebook.
2. Run all cells in order.
3. Dataset is loaded directly from the UCI repository.

---

## Author

Biomedical Engineer  
Focused on Healthcare Data Analysis and Machine Learning
