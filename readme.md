# 📊 Telecom Churn Prediction

## Overview
This project predicts customer churn in the telecom industry using Machine Learning and exploratory data analysis.

The objective is to identify customers likely to leave and generate business insights for customer retention.

---

## Problem Statement
Customer churn leads to revenue loss.

Goal:
- Predict churn
- Understand churn drivers
- Support retention strategies

---

## Tech Stack

### Language
- Python

### Libraries
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Project Workflow

### 1. Data Loading
```python
import pandas as pd

df = pd.read_csv("telecom_churn.csv")
```

---

## 2. Data Cleaning
- Handle missing values
- Remove duplicates
- Encode categorical variables
- Feature scaling

---

## 3. Exploratory Data Analysis
Performed analysis on:

- Customer tenure
- Monthly charges
- Contract type
- Payment method
- Churn distribution

Example:

```python
sns.countplot(x='Churn', data=df)
```

---

## 4. Feature Engineering
Created:
- Tenure groups
- Encoded features
- Derived variables

---

## 5. Machine Learning Models
Used:
- Logistic Regression
- Decision Tree
- Random Forest

Example:

```python
from sklearn.ensemble import RandomForestClassifier

model = RandomForestClassifier()
model.fit(X_train,y_train)
```

---

## Model Evaluation
Metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC AUC

Example Results:

| Model | Accuracy |
|------|----------|
| Logistic Regression | 80% |
| Decision Tree | 82% |
| Random Forest | 86% |

---

## Key Insights
- Short tenure customers churn more
- High monthly charges increase churn risk
- Month-to-month contracts have higher churn

---

## Business Impact
This solution helps:
- Reduce churn
- Improve retention
- Identify high-risk customers
- Support business decisions

---

## Repository Structure

```bash
Telecom-Churn-Prediction/
│
├── Telecom_Churn.ipynb
├── telecom_churn.csv
├── requirements.txt
└── README.md
```

---

## Installation

Clone repository:

```bash
git clone https://github.com/yourusername/Telecom-Churn-Prediction.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run:

```bash
jupyter notebook
```

---

## requirements.txt

```bash
pandas
numpy
matplotlib
seaborn
scikit-learn
```

---

## Future Improvements
- Hyperparameter tuning
- Model deployment
- Dashboard integration

---

## Skills Demonstrated
- Data Cleaning
- EDA
- Machine Learning
- Model Evaluation
- Business Analytics

---

## Author
Raja Rajeswari Chandni P  
Data Analyst | Python | SQL | Machine Learning

LinkedIn:
www.linkedin.com/in/chandni-p-849532284
