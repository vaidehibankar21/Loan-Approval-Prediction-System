# Loan Approval Prediction System

> An End-to-End Machine Learning Classification Project using Python and Scikit-Learn

---

# Project Overview

Financial institutions receive thousands of loan applications every day. One of the major challenges is identifying applicants who are likely to repay their loans while minimizing the risk of defaults.

This project develops an end-to-end Machine Learning pipeline that predicts loan approval based on an applicant's demographic, financial, and credit history information.

The project follows the complete Machine Learning lifecycle including:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Building
- Hyperparameter Tuning
- Model Evaluation
- Model Deployment Pipeline

---

# Business Problem

Approving loans without proper risk assessment may lead to financial losses due to defaults.

Rejecting too many applicants, on the other hand, reduces business opportunities and customer satisfaction.

The objective is to build a predictive system that helps financial institutions make faster and more informed lending decisions.

---

# Objectives

- Predict whether a loan application will be approved.
- Reduce lending risk.
- Compare multiple Machine Learning models.
- Improve prediction performance through hyperparameter tuning.
- Build a reusable prediction pipeline.

---

# Dataset

The dataset contains historical loan application records.
Source : "https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset"

### Features

- Loan_ID
- Gender
- Married
- Dependents
- Education
- Self_Employed
- ApplicantIncome
- CoapplicantIncome
- LoanAmount
- Loan_Amount_Term
- Credit_History
- Property_Area

### Target Variable

Loan_Status

- Y → Loan Approved
- N → Loan Rejected

---

# ⚙️ Machine Learning Workflow

```
Loan Data
      │
      ▼
Data Cleaning
      │
      ▼
Exploratory Data Analysis
      │
      ▼
Feature Engineering
      │
      ▼
Encoding
      │
      ▼
Feature Scaling
      │
      ▼
Train-Test Split
      │
      ▼
Model Training
      │
      ▼
Hyperparameter Tuning
      │
      ▼
Model Evaluation
      │
      ▼
Prediction Pipeline
```

---

# Exploratory Data Analysis

Key insights obtained from the data include:

- Credit History is the strongest predictor of loan approval.
- Applicant Income alone does not guarantee loan approval.
- Loan Amount contains several outliers.
- Numerical variables exhibit skewed distributions.
- No severe multicollinearity exists among numerical features.

---

# Machine Learning Models

The following models were trained and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

Evaluation Metrics:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix
- ROC Curve

---

# Best Model

After comparing all models, **Logistic Regression** achieved the best overall performance and was selected as the final model.

### Hyperparameter Tuning

GridSearchCV was used to optimize:

- Regularization Strength (C)
- Solver

---

# Project Visualizations

The repository contains the following visualizations:

- Loan Status Distribution
- Credit History vs Loan Status
- Correlation Heatmap
- Model Comparison
- Confusion Matrix
- ROC Curve
- Feature Importance

---

# 🛠 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Joblib
- Google Colab

---

# Project Structure

```
Loan-Approval-Prediction-System/
│
├── data/
│   └── loan_data.csv
│
├── notebook/
│   └── Loan_Approval_Prediction.ipynb
│
├── model/
│   └── loan_prediction_pipeline.pkl
│
├── images/
│
├── summary/
│
├── README.md
├── requirements.txt
└── LICENSE
```


---

# ▶️ How to Run

1. Open the Jupyter Notebook.
2. Execute all notebook cells sequentially.
3. Train the machine learning models.
4. Evaluate model performance.
5. Use the saved pipeline to make predictions for new loan applicants.

---

**Vaidehi Bankar**

B.Tech Computer Science Engineering Student

Machine Learning | Data Science | Artificial Intelligence

---

#  If you found this project helpful, consider giving it a star!
