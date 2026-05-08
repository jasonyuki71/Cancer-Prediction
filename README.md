# Cancer Prediction Project

<div align="center">
    <img src="image/cancer1.jpg" width="600">
</div>

## Overview

This project explores demographic, lifestyle, and genetic factors associated with cancer diagnosis using statistical analysis and machine learning techniques.

The study applies exploratory data analysis (EDA), statistical hypothesis testing, and logistic regression modeling to identify important predictors of cancer and evaluate predictive performance.

---

## Objectives

- Analyze relationships between health-related variables and cancer diagnosis
- Identify important cancer risk factors
- Build a predictive classification model using Logistic Regression
- Evaluate model performance using multiple classification metrics

---

## Dataset Features

The dataset includes variables such as:

- Age
- BMI
- Gender
- Smoking Status
- Alcohol Intake
- Physical Activity
- Genetic Risk
- Cancer History
- Diagnosis (Target Variable)

---

## Exploratory Data Analysis

The project includes:

- Distribution analysis
- Comparative analysis between cancer and non-cancer patients
- Statistical summary tables
- Correlation analysis
- Risk factor interpretation

---

## Statistical Analysis

Statistical methods used include:

- Independent t-tests
- Effect size analysis (Cohen’s d)
- Risk ratio analysis
- Comparative proportion analysis

---

## Machine Learning Model

A multivariate Logistic Regression model was implemented to predict cancer diagnosis probability.

### Model Evaluation Metrics

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC
- Confusion Matrix

### Model Performance

| Metric | Score |
|---|---|
| Accuracy | 84.33% |
| ROC-AUC | 0.917 |
| Precision | 79.63% |
| Recall | 77.48% |

The model demonstrated strong predictive performance with minimal overfitting.

---

## Key Findings

- Cancer patients were generally older and had higher BMI values.
- Smoking, genetic risk, and cancer history showed strong associations with cancer diagnosis.
- Physical activity demonstrated a negative relationship with predicted cancer risk.
- Logistic Regression achieved strong classification performance using demographic and health-related features.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Repository Structure

```text
├── Cancer_Prediction.ipynb
├── cancer.jpg
├── dataset.csv
├── README.md
```

---

## Ethical Considerations

This project is intended for educational and research purposes only. Predictive models should not replace professional medical diagnosis, and healthcare-related machine learning applications must consider fairness, bias, privacy, and clinical responsibility.

---

## Author

Hsin Yu Ho
UC San Diego – Data Science