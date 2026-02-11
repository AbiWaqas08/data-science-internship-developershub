# Task 2: Credit Risk Prediction

## Objective
The objective of this project is to predict whether a loan applicant is
likely to default on a loan based on demographic and financial features.
This is a binary classification problem commonly used in the banking and
financial sector for credit risk assessment.

---

## Dataset
- **Name:** Loan Prediction Dataset  
- **Source:** Kaggle  
- **Dataset Link:**  
  https://www.kaggle.com/datasets/altruistdelhite04/loan-prediction-problem-dataset
- Download Train dataset from this link
### Description
The dataset contains information about loan applicants, including:
- Gender
- Marital Status
- Education
- Applicant Income
- Loan Amount
- Credit History
- Loan Status (Target Variable)

---

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## Approach

### 1. Data Understanding
- Examined dataset structure, data types, and summary statistics
- Identified numerical and categorical features
- Checked for missing values

### 2. Data Cleaning
- Filled missing categorical values using mode
- Filled missing numerical values using median
- Encoded categorical variables using Label Encoding

### 3. Exploratory Data Analysis (EDA)
- Analyzed loan approval distribution
- Visualized loan amount vs loan status
- Studied relationship between education and loan approval

### 4. Model Building
- Split data into training and testing sets
- Trained a Logistic Regression model
- Generated predictions on test data

### 5. Model Evaluation
- Evaluated performance using accuracy score
- Used confusion matrix and classification report

---

## Results & Insights
- Logistic Regression achieved reliable classification accuracy
- Credit history and income play a significant role in loan approval
- The model can assist banks in minimizing loan default risk

---

## Conclusion
This project demonstrates a complete machine learning workflow for
credit risk prediction, including data cleaning, visualization, model
training, and evaluation. Such models are essential for making informed,
data-driven financial decisions in real-world banking systems.

---

## Project Structure
Task_2_Credit_Risk/
│
├── credit_risk.ipynb
└── README.md