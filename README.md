# Prediction-of-Diabetes
# Diabetes Prediction Project

**Project Type:** Machine Learning – Classification  
**Goal:** Predict diabetes (`Outcome`) based on medical and demographic features.
This project demonstrates a complete workflow for predicting diabetes using a structured dataset. The goal is to predict whether a patient has diabetes (Outcome) based on medical and demographic features.

---

## Project Overview

The project includes the following steps:

1. **Data Loading**  
   Loading the dataset from CSV and inspecting its structure.

2. **Data Cleaning & Preprocessing**  
    - Handles missing values using **KNN Imputer** .
    - Detects and corrects inconsistencies in categorical data.
    - Removes duplicates and invalid records.
    - Provides clear visualizations for data understanding.
    - Prepares data for modeling using clean and well-structured features.
3. **Exploratory Data Analysis (EDA)**  
   Analyzing the distribution of features, visualizing relationships, and understanding correlations.

4. **Feature Engineering**  
   Creating or transforming features to improve model performance.

5. **Modeling**  
   - **Models:** Decision Tree, Logistic Regression  
   - Tuned logistic regression achieved the best metrics (f1-score, recall, accuracy)  
   - Evaluation performed on train, validation, and test sets  
6. **Evaluation**  
   Evaluating models using metrics such as accuracy, confusion matrix, and classification reports.

---

## Dataset

The dataset includes the following features:

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- DiabetesPedigreeFunction
- WeightGroup
- AgeGroup
- Gender
- Outcome (target variable)

---

## Tools Used

- Python
- Pandas & NumPy for data manipulation
- Matplotlib & Seaborn for visualization
- Scikit-learn for preprocessing and modeling
- Google Colab for running the project

---

## Recommendations

- Increase dataset size for better generalization  
- Balance categorical features like `AgeGroup` and `Gender`  
- Monitor feature distributions to reduce bias


