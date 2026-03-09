# Customer_Churn_Prediction
ML and RNN based customer churn prediction

---

# Customer Churn Prediction using Machine Learning and RNN

## 📌 Project Overview

Customer churn prediction is a critical task for businesses that want to retain customers and reduce revenue loss.  
This project focuses on predicting whether a customer will **churn (leave the service)** or **stay** using Machine Learning and Deep Learning models.

The project applies **data analysis, feature engineering, machine learning models and Recurrent Neural Networks (RNN)** to build an accurate churn prediction system.

---

# 🎯 Project Objectives

- Analyze customer behavior and service usage
- Identify factors that contribute to customer churn
- Build predictive models to classify churn vs non-churn customers
- Compare Machine Learning and Deep Learning models
- Provide business insights to reduce churn rate

---

# 🧠 Problem Statement

Customer churn occurs when customers stop using a company's service.  
Losing customers directly impacts company revenue and growth.

The objective of this project is to build predictive models that can identify **customers who are likely to churn**, allowing companies to take **preventive actions and retention strategies**.

---

# 📊 Dataset

Dataset used in this project:

**Telco Customer Churn Dataset**

Dataset contains information about:

- Customer demographics
- Account information
- Internet services
- Billing details
- Contract type
- Payment method
- Customer tenure

---

### Target Variable

Churn

Values:
Yes → Customer left the service
No → Customer stayed

---

# 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras
- Jupyter Notebook

---

# ⚙️ Project Workflow

The project follows the complete machine learning pipeline:

Data Collection
↓
Data Exploration (EDA)
↓
Data Cleaning
↓
Feature Engineering
↓
Data Preprocessing
↓
Model Training
↓
Model Evaluation
↓
Model Comparison
↓
Business Insights

## Project Structure

Customer-Churn-Prediction
│
├── data
│ └── telco_churn.csv

├── notebook

├── models

├── results

└── README.md

---

## 🚀 How to Run the Project

1.Clone the repository

git clone https://github.com/chinnarasan007/Customer_Churn_Prediction/tree/main

2.Install dependencies

pip install -r requirements.txt

3.Run the notebook

jupyter notebook

---

# 📊 Exploratory Data Analysis (EDA)

During EDA we analyzed:

- Customer tenure
- Monthly charges
- Contract type
- Payment methods
- Internet services
- Churn distribution

### Key Observations

- Customers with **short tenure churn more frequently**
- **Month-to-month contracts** have higher churn rates
- Customers with **higher monthly charges** show increased churn probability
- Long-term contracts reduce churn risk

---

# 🤖 Machine Learning Models Used

The following models were implemented:

### 1️⃣ Logistic Regression
Baseline classification model used for binary prediction.

### 2️⃣ Random Forest
Ensemble learning method that combines multiple decision trees.

### 3️⃣ LSTM (Recurrent Neural Network)
Deep learning model used to capture complex relationships within the dataset.

---

# 📈 Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- Confusion Matrix

---

# 📊 Model Performance Comparison

| Model | Accuracy |
|------|------|
| Logistic Regression | ~79% |
| Random Forest | ~79% |
| LSTM | ~79% |

The **LSTM model achieved the highest performance** in predicting customer churn.

---

# 📉 Confusion Matrix

Confusion matrices were generated for each model to analyze:

- True Positives
- True Negatives
- False Positives
- False Negatives

These metrics help evaluate classification performance beyond accuracy.

---

# 💡 Business Insights

From the analysis, the following insights were discovered:

1. Customers with **short tenure** have higher churn probability.
2. **High monthly charges** increase the likelihood of churn.
3. Customers with **month-to-month contracts** churn more frequently.
4. Customers using **long-term contracts** are more likely to stay.

---

# 📢 Business Recommendations

Companies can reduce churn by:

- Offering loyalty discounts for long-term customers
- Providing better pricing for high monthly charge users
- Encouraging customers to switch to yearly contracts
- Improving customer support services
- Identifying high-risk customers early using predictive models

---

# 🚀 Future Improvements

Possible improvements for this project include:

- Hyperparameter tuning using GridSearchCV
- Implementing additional boosting models (LightGBM, CatBoost)
- Building a real-time churn prediction dashboard
- Deploying the model using Streamlit or Flask
- Integrating the model into a production system

---

# 🎯 Conclusion

This project demonstrates how **Machine Learning and Deep Learning models** can be applied to predict customer churn effectively.

By analyzing customer behavior and building predictive models, businesses can identify at-risk customers and implement strategies to improve retention and reduce revenue loss.

---

# 👨‍💻 Author

**Chinnarajan M**

Aspiring Data Scientist

---
