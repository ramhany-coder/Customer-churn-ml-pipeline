# End-to-End Bank Churn Prediction

An end-to-end Machine Learning project for predicting customer churn in the banking sector using data preprocessing, feature engineering, SMOTE imbalance handling, model comparison, and hyperparameter tuning.

---

# Project Overview

Customer churn is one of the major challenges in the banking industry.  
This project aims to predict whether a customer is likely to leave the bank based on demographic and financial information.

The system helps banks:
- Identify high-risk customers
- Improve retention strategies
- Reduce customer acquisition costs
- Support data-driven decision making

---

# Problem Statement

Banks lose revenue when customers leave their services or move to competitors.

This project builds a Machine Learning pipeline capable of predicting customer churn using historical banking data.

Target Variable:
- `Exited = 1` → Customer left the bank
- `Exited = 0` → Customer stayed

---

# Dataset Features

| Feature | Description |
|---|---|
| CreditScore | Customer credit score |
| Geography | Customer country |
| Gender | Customer gender |
| Age | Customer age |
| Tenure | Years with the bank |
| Balance | Account balance |
| NumOfProducts | Number of bank products |
| HasCrCard | Owns a credit card |
| IsActiveMember | Activity status |
| EstimatedSalary | Estimated salary |
| Exited | Churn target variable |

---

# Project Workflow

```text
Data Collection
        ↓
Data Cleaning
        ↓
Exploratory Data Analysis (EDA)
        ↓
Feature Engineering
        ↓
Handling Imbalanced Data (SMOTE)
        ↓
Train/Test Split
        ↓
Model Training
        ↓
Hyperparameter Tuning
        ↓
Model Evaluation
        ↓
Prediction & Insights
```

---

# Technologies Used

## Programming Language
- Python

## Libraries
- pandas
- numpy
- matplotlib
- scikit-learn
- imbalanced-learn
- xgboost

---

# Machine Learning Techniques

The project includes:
- Data preprocessing
- One-hot encoding
- Feature scaling
- Handling imbalanced data using SMOTE
- Classification model training
- Hyperparameter tuning
- Performance evaluation

---

# Models Used

- Logistic Regression
- Random Forest
- Support Vector Machine (SVM)
- XGBoost
- Naive Bayes

---

# Evaluation Metrics

Models were evaluated using:
- Accuracy
- Precision
- Recall
- F1-Score
- Confusion Matrix
- ROC-AUC Score

---

# Why SMOTE Was Used

The dataset contains class imbalance where non-churn customers significantly outnumber churn customers.

SMOTE (Synthetic Minority Oversampling Technique) was applied to improve the model’s ability to correctly identify churned customers.

This improves:
- Recall
- Minority class detection
- Overall model robustness

---

# Key Insights

Some important observations discovered during analysis:

- Active members are less likely to churn
- Older customers show higher churn probability
- Geography impacts churn behavior
- Customers with fewer products are more likely to leave
- Balance and customer activity strongly influence retention

---

# Business Impact

This system can help banks:
- Prioritize high-risk customers
- Improve retention workflows
- Reduce manual analysis effort
- Support customer loyalty strategies
- Enable data-driven decisions

---

# Repository Structure

```text
Bank-Churn-Prediction/
│
├── data/
├── notebooks/
│   └── Bank_Churn_Model_ML_project.ipynb
│
├── models/
├── requirements.txt
├── README.md
└── .gitignore
```

---

# Future Improvements

Possible future enhancements include:
- Deploying the model using FastAPI
- Dockerizing the application
- Building an interactive Streamlit dashboard
- Creating a real-time prediction API
- Cloud deployment
- Model monitoring and logging

---

# Example Use Case

```python
customer_data = {
    "CreditScore": 650,
    "Age": 45,
    "Balance": 120000,
    "IsActiveMember": 0
}
```

Output:

```python
Prediction: Customer likely to churn
```

---

# Installation

Clone the repository:

```bash
git clone <your-repository-link>
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the notebook:

```bash
jupyter notebook
```

---

# Results

The project successfully demonstrates:
- End-to-end ML workflow
- Handling imbalanced datasets
- Model comparison and tuning
- Business-oriented churn analysis

---

# Author

## Ram Hany Awad

AI Engineer & Machine Learning Developer with a background in Mechatronics Engineering and AI systems development. Experienced in building end-to-end AI solutions including Machine Learning pipelines, RAG systems, NLP applications, and Computer Vision models using Python, TensorFlow, PyTorch, and Scikit-Learn.

- GitHub: :(https://github.com/ramhany-coder)
- LinkedIn: :www.linkedin.com/in/ram-hany-96a34b35a

---

## Project Partner

### :Youssef Rady

AI & Machine Learning enthusiast and project collaborator contributing to the development and evaluation of the customer churn prediction pipeline.

- LinkedIn: :https://www.linkedin.com/in/youssef-ahmed-rady?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)
