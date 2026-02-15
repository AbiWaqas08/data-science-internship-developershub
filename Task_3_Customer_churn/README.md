# Task 3: Customer Churn Prediction (Bank Customers)

## 📌 Objective
The objective of this project is to identify bank customers who are likely
to leave (churn). Predicting customer churn helps financial institutions
take proactive steps to retain high-risk customers and reduce revenue loss.

---

## 📊 Dataset
- **Name:** Churn Modelling Dataset  
- **Source:** Kaggle  
- **Dataset Link:**  
  https://www.kaggle.com/datasets/shrutimechlearn/churn-modelling

### Description
The dataset contains customer information including:
- Credit Score
- Geography
- Gender
- Age
- Tenure
- Account Balance
- Number of Products
- Has Credit Card
- Is Active Member
- Estimated Salary
- Exited (Target Variable: 1 = Churned, 0 = Stayed)

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Approach

### 1. Data Cleaning & Preparation
- Removed irrelevant columns (RowNumber, CustomerId, Surname)
- Checked and handled missing values (if any)

### 2. Categorical Encoding
- Label Encoding applied to Gender
- One-Hot Encoding applied to Geography

### 3. Exploratory Data Analysis (EDA)
- Analyzed churn distribution
- Studied impact of Age and Balance on churn
- Identified key behavioral patterns

### 4. Model Training
- Split dataset into training and testing sets
- Trained Random Forest Classifier
- Generated predictions on test data

### 5. Model Evaluation
- Evaluated using Accuracy Score
- Analyzed Confusion Matrix
- Interpreted Feature Importance

---

## 📈 Key Insights
- Age is one of the strongest predictors of churn.
- Customers with higher balances show different churn behavior.
- Geography influences customer retention patterns.
- Feature importance analysis helps identify high-risk segments.

---

## 📊 Model Performance
- Classification Model: Random Forest
- Evaluation Metrics: Accuracy & Confusion Matrix
- Model achieved strong predictive performance on test data.

---

## ✅ Conclusion
This project demonstrates a complete machine learning workflow for
customer churn prediction. By analyzing customer behavior and identifying
important features, the model provides valuable insights that can help
banks implement targeted retention strategies.

---

## 📂 Project Structure

Task_3_Customer_Churn_Prediction/
│
├── churn_prediction.ipynb
└── README.md