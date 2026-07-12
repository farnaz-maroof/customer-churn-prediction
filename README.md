# Customer Churn Prediction using Machine Learning

## Project Overview

Customer churn is one of the most important challenges for subscription-based businesses. Retaining existing customers is generally more cost-effective than acquiring new ones. This project analyzes customer behavior and develops machine learning models to predict whether a customer is likely to churn.

The project includes data preprocessing, exploratory data analysis (EDA), feature engineering, model development, hyperparameter tuning, and business recommendations based on the findings.

---

## Objectives

The main objectives of this project are:

- Explore customer characteristics related to churn.
- Identify the key factors influencing customer churn.
- Build and compare multiple machine learning models.
- Select the best-performing model for churn prediction.
- Provide business recommendations to improve customer retention.

---

## Dataset

The dataset contains customer demographic information, subscribed services, contract details, billing information, and churn status.

Target Variable:

- *Churn*
  - Yes
  - No

---

## Project Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Splitting
5. Model Development
   - Logistic Regression
   - Decision Tree
   - Random Forest
   - XGBoost
6. Hyperparameter Tuning using GridSearchCV
7. Model Evaluation
8. Model Comparison
9. Business Insights and Recommendations

---

## Machine Learning Models

The following models were implemented and evaluated:

- Logistic Regression
- Decision Tree
- Tuned Decision Tree
- Random Forest
- Tuned Random Forest
- XGBoost
- Tuned XGBoost

Evaluation metrics include:

- Accuracy
- Precision
- Recall
- F1-score
- ROC Curve
- AUC
- Train/Test Accuracy

---

## Results

After comparing all models, the *Tuned XGBoost* model achieved the best overall performance.

Key observations:

- Highest overall Accuracy
- Highest AUC score
- Better generalization
- Reduced overfitting after hyperparameter tuning

---

## Business Insights

The analysis showed that customer churn is strongly associated with:

- Month-to-month contracts
- Short customer tenure
- Higher monthly charges
- Fiber Optic internet service
- Lack of Online Security and Tech Support services

Customers with long-term contracts and additional support services were less likely to churn.

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

---

## Repository Structure


Customer-Churn-Prediction/
│
├── data/
├── notebooks/
├── outputs/
├── README.md
└── requirements.txt


---

## Conclusion

This project demonstrates how machine learning can be used to predict customer churn and support business decision-making. Among all evaluated models, the tuned XGBoost classifier provided the best balance between predictive performance and generalization, making it the most suitable model for customer churn prediction.
