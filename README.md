# Heart Failure Mortality Prediction

This project aims to build a machine learning model that predicts the mortality of patients suffering from heart failure based on various clinical features. It uses a publicly available dataset from Kaggle and demonstrates preprocessing, exploratory data analysis (EDA), modeling, evaluation, and interpretation.

## 📁 Dataset

- Source: Kaggle – [Heart Failure Prediction Dataset]
- Features: 12 clinical variables (e.g., age, ejection fraction, serum creatinine)
- Target: DEATH_EVENT (1 = died during follow-up, 0 = survived)

## 🧠 Problem Statement

To develop a binary classification model that can accurately predict whether a patient will die due to heart failure, based on medical attributes.

## 🔧 Technologies Used

- Python (Jupyter Notebook)
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn, imbalanced-learn

## 📊 Project Workflow

1. **Data Loading**
   - Importing the dataset
   - Checking for nulls and data types

2. **Exploratory Data Analysis (EDA)**
   - Class balance analysis
   - Correlation heatmap
   - Distributions of features

3. **Data Preprocessing**
   - Train-test split
   - Standardization using `StandardScaler`
   - Balancing classes with SMOTE (optional)

4. **Modeling**
   - Random Forest Classifier
   - Logistic Regression
   - Cross-validation (5-fold)
   - ROC AUC score, classification report

5. **Feature Importance**
   - Bar plots for feature importances (Random Forest)
   - Coefficients for Logistic Regression

## 📈 Results

- Evaluated using:
  - Classification Report (Precision, Recall, F1-score)
  - ROC AUC Score
- Feature importance showed that age, serum creatinine, and ejection fraction were strong indicators of mortality.

## 🔍 Key Insights

- Imbalanced data required SMOTE for better generalization.
- Logistic Regression offered interpretability.
- Random Forest achieved high accuracy with solid feature ranking.
