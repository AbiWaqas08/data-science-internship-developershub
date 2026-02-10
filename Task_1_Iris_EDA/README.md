# Task 1: Exploring and Visualizing the Iris Dataset

## Objective
The objective of this task is to explore and visualize the Iris dataset in order to
understand its structure, feature distributions, relationships between variables,
and potential outliers using data analysis and visualization techniques.

---

## Dataset
- **Name:** Iris Dataset
- **Source:** Seaborn built-in dataset
- **Description:**  
  The dataset consists of 150 samples of iris flowers with the following features:
  - Sepal Length
  - Sepal Width
  - Petal Length
  - Petal Width
  - Species (Setosa, Versicolor, Virginica)

---

## Tools & Libraries
- Python
- Pandas
- Matplotlib
- Seaborn

---

## Approach

### 1. Data Loading & Inspection
- Loaded the dataset using Seaborn
- Examined dataset shape, columns, and sample records
- Reviewed data types and summary statistics

### 2. Exploratory Data Analysis (EDA)
- **Scatter Plot:** Analyzed relationships between sepal dimensions
- **Histograms:** Studied feature distributions
- **Box Plots:** Identified data spread and potential outliers
- **Species-wise Comparison:** Compared petal measurements across species

---

## Key Insights
- Petal features (length and width) clearly distinguish different iris species
- Iris-setosa is easily separable from other species
- Sepal features show more overlap between species
- No significant missing values or extreme outliers found

---

## Conclusion
This task provided a strong foundation in data exploration and visualization.
Understanding feature behavior and relationships through EDA is essential
before applying machine learning models. The Iris dataset is clean, well-structured,
and suitable for further classification tasks.

---

## 📂 Project Structure
Task_1_Iris_EDA/
│
├── iris_eda.ipynb
└── README.md