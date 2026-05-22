<h1 style="text-align: center; color: blue;">Predicting Loan Default Risk Using Machine Learning</h1>

## End-to-End Credit Risk Analytics & Explainable AI Project

![Python](https://img.shields.io/badge/Python-3.10-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-XGBoost%20%7C%20LightGBM-green)
![Status](https://img.shields.io/badge/Status-Completed-success)

---

## Project Overview

This project develops a machine learning framework for predicting borrower loan default risk using the Home Credit Default Risk dataset from Kaggle.

The workflow combines:

- Credit Risk Analytics
- Machine Learning
- Explainable AI (SHAP)
- Feature Engineering
- Imbalanced Learning
- Business Interpretation

The objective is to help financial institutions:
- Identify high-risk borrowers
- Reduce non-performing loans
- Improve underwriting decisions
- Support data-driven lending systems

---

# Dataset

Dataset Source:

https://www.kaggle.com/competitions/home-credit-default-risk

Due to Kaggle competition restrictions, the dataset is not included in this repository.

Please download:
- `application_train.csv`
- `application_test.csv`

and place them inside:

```bash
credit_data/
```

---

# Models Implemented

- Logistic Regression
- Random Forest
- XGBoost
- LightGBM

---

# Key Features

## Exploratory Data Analysis
- Missing value analysis
- Class imbalance visualization
- Correlation heatmaps

## Feature Engineering
Created custom financial indicators such as:
- Credit-to-Income Ratio
- Annuity-to-Income Ratio
- Employment-to-Age Ratio

## Explainable AI
Implemented SHAP explainability for model transparency and feature interpretation.

## Model Evaluation
Performance evaluated using:
- ROC-AUC
- Precision
- Recall
- F1-Score
- Confusion Matrix

---

# Model Performance

| Model | ROC-AUC |
|---|---|
| Logistic Regression | 0.620 |
| Random Forest | 0.683 |
| XGBoost | 0.754 |
| LightGBM | 0.758 |

---

# Technologies Used

- Python
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- SHAP
- Matplotlib
- Seaborn
- Jupyter Notebook

---

# Project Structure

```bash
home-credit-default-risk/
│
├── credit_data/
├── notebooks/
├── figures/
├── models/
└── README.md
```

---

The **figures directory** contains the following figures and tables.

```bash
figures/
│
├── missing_values_plot.png
├── class_imbalance_plot.png
├── correlation_heatmap.png
├── model_performance_comparison.png
├── roc_curve_comparison.png
├── feature_importance.png
├── shap_summary_plot.png
├── confusion_matrix.png
├── model_performance_table.csv
└── feature_importance_table.csv
```
---

# Installation

```bash
git clone https://github.com/elijah-appiah/ml-credit-risk-default-project.git
cd ml-credit-risk-default-project
```

---

# Running the Notebook

```bash
jupyter notebook
```

Open:

```bash
notebooks/credit_risk_model.ipynb
```

---

# Business Insight

The project demonstrates how machine learning can improve credit allocation efficiency and enhance financial decision-making through interpretable AI systems.

Gradient boosting models significantly outperformed traditional linear approaches, highlighting the importance of nonlinear learning in financial risk prediction.

---

# Future Improvements

- Hyperparameter optimization
- Streamlit dashboard deployment
- MLOps integration
- Fairness and bias auditing
- Deep learning extensions

---

# Author

## Elijah Appiah

PhD Economics Candidate | Data Scientist

---

# License

MIT License
