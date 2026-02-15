# Task 4: Predicting Insurance Claim Amounts

## 📌 Objective
The objective of this project is to estimate medical insurance charges based on personal and health-related information such as age, BMI, smoking status, and number of dependents.

This is a supervised machine learning regression problem where the target variable is continuous (insurance charges).

---

## 📊 Dataset
- **Name:** Medical Cost Personal Dataset
- **Source:** Kaggle
- **Link:** https://www.kaggle.com/datasets/mirichoi0218/insurance

### Dataset Features
- age → Age of the insured person
- sex → Gender
- bmi → Body Mass Index
- children → Number of dependents
- smoker → Smoking status (Yes/No)
- region → Residential region
- charges → Medical insurance cost (Target Variable)

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1️⃣ Data Loading
Loaded the dataset using Pandas and explored its structure using `.head()`, `.info()`, and `.describe()`.

### 2️⃣ Data Cleaning & Preprocessing
- Checked for missing values
- Applied One-Hot Encoding to categorical variables (sex, smoker, region)
- Separated features (X) and target variable (y)
- Split the dataset into training and testing sets

### 3️⃣ Exploratory Data Analysis (EDA)
Visualized relationships between:
- Age vs Insurance Charges
- BMI vs Insurance Charges
- Smoking Status vs Charges

### Key Observations:
- Smoking status significantly increases insurance charges.
- Age shows a positive correlation with charges.
- Higher BMI tends to increase insurance cost.

### 4️⃣ Model Training
- Trained a Linear Regression model on training data.

### 5️⃣ Model Evaluation
Evaluated model performance using:
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

These metrics measure prediction accuracy and error magnitude.

---

## 📈 Results
- Model Type: Linear Regression
- Evaluation Metrics: MAE and RMSE
- The model provides reasonable prediction accuracy for insurance cost estimation.
- Smoking status was one of the strongest influencing factors.

---

## ✅ Conclusion
This project demonstrates a complete regression workflow including data preprocessing, visualization, model training, and evaluation. The analysis highlights that lifestyle factors, especially smoking, significantly impact medical insurance charges.

The model can be further improved using advanced regression techniques such as Polynomial Regression or Regularization methods.

---

## 📂 Project Structure
Task_4_Insurance_Regression/
│
├── insurance_regression.ipynb
└── README.md