# Cancer Prediction Project

<div align="center">
    <img src="image/cancer1.jpg" width="800">
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

- **Accuracy** measures the overall percentage of correct predictions made by the model.

- **Precision** measures how many patients predicted as cancer cases were actually diagnosed with cancer.

- **Recall** measures how effectively the model identified actual cancer patients.

- **F1 Score** balances precision and recall, providing an overall measure of classification quality.

- **ROC-AUC** evaluates the model’s ability to distinguish between cancer and non-cancer patients across different classification thresholds.

The model achieved strong overall performance, with an ROC-AUC score above 0.91, indicating excellent discriminative capability between positive and negative cancer diagnoses.

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
## Feature Selection

Compared to more complex machine learning models, logistic regression also offers lower computational cost, reduced overfitting risk, and greater interpretability for healthcare-related applications.

The variables included in the logistic regression model were selected based on both statistical analysis results and domain relevance to cancer risk.

Features such as age, BMI, smoking status, alcohol intake, physical activity, genetic risk, and cancer history demonstrated statistically significant differences between cancer and non-cancer groups during exploratory data analysis and hypothesis testing.

These variables were chosen because prior medical research and the statistical findings from this project suggest that they may contribute meaningfully to cancer diagnosis prediction.

Gender was also included as a demographic variable to evaluate potential differences in cancer prevalence across patient groups.

### Why Logistic Regression?

Logistic Regression was selected because the target variable (cancer diagnosis) is binary, making it well-suited for classification tasks. In addition to strong predictive performance, logistic regression provides interpretable feature coefficients, allowing the relative influence of different health and lifestyle variables on cancer prediction to be analyzed directly.

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
