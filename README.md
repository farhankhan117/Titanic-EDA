# 🚢 Titanic Dataset – Exploratory Data Analysis (EDA)

## 🎯 Objective
Perform **Exploratory Data Analysis (EDA)** on the Titanic dataset to understand data distributions, handle missing values, encode categorical variables, scale numerical features, and remove outliers in preparation for machine learning models.

---

## 🛠 Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## 🔍 Summary of Steps
### 1. Data Exploration
- Loaded the dataset
- Examined data structure, data types, and summary statistics

### 2. Handling Missing Values
- Filled missing values in **Age** using the median
- Filled missing values in **Embarked** using the mode
- Dropped the **Cabin** column due to excessive missing values

### 3. Encoding Categorical Variables
- Applied **Label Encoding** on the **Sex** column
- Applied **One-Hot Encoding** on the **Embarked** column

### 4. Feature Scaling
- Standardized numerical features:
  - **Age**
  - **Fare**

### 5. Outlier Detection & Removal
- Visualized outliers using boxplots
- Removed records with **Fare > 300**

### 6. Final Dataset Preparation
- Generated a clean and processed dataset
- Dataset is now ready for modeling and further analysis

---

## 📊 Key Insights
- Age and Fare show skewed distributions requiring scaling
- Passenger survival patterns vary significantly by gender and class
- High Fare values introduce outliers that can negatively impact models

---

## ✅ Conclusion
The Titanic dataset has been successfully cleaned and explored:
- No missing values remain
- Categorical variables are properly encoded
- Numerical features are standardized
- Outliers have been handled effectively

The dataset is now suitable for machine learning modeling and advanced analysis.

---

## 📁 Project Files
- `Titanic-Dataset.csv` – Raw dataset  
- `Titanic_EDA.ipynb` – EDA notebook and visualizations  
- `README.md` – Project documentation  

---

## 🚀 Next Steps
- Build classification models (Logistic Regression, Random Forest, XGBoost)
- Perform feature importance analysis
- Evaluate model performance using accuracy, precision, recall, and ROC-AUC


---
