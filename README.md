# 🧹 Titanic Data Cleaning Project

## 📌 Project Overview

This project demonstrates a complete data cleaning workflow using the Titanic dataset.

The main objective is to transform raw and potentially inconsistent data into a clean, analysis-ready dataset using Python and Pandas.

The project focuses on identifying data quality issues, handling missing values, removing duplicates, standardizing data, detecting outliers, and correcting data types.

---

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 📂 Dataset

The project uses the Titanic `train.csv` dataset.

The dataset contains information about passengers, including:

- Passenger ID
- Survival status
- Passenger class
- Name
- Gender
- Age
- Number of siblings/spouses
- Number of parents/children
- Ticket
- Fare
- Embarked port

---

## 🔍 Data Cleaning Process

### 1. Data Quality Report

The dataset was inspected to identify:

- Missing values
- Duplicate records
- Incorrect data types
- Invalid numeric values
- Potential outliers
- Data inconsistencies

### 2. Missing Value Handling

Missing values were analyzed column by column.

Appropriate strategies were applied based on the nature of the data, such as:

- Median imputation for numerical data
- Mode imputation for categorical data
- Row removal where appropriate

### 3. Duplicate Removal

Duplicate records were identified and removed to prevent repeated observations from affecting the analysis.

### 4. Data Standardization

Inconsistent data formats were standardized.

Examples include:

- Converting categorical values into consistent formats
- Converting dates where applicable
- Standardizing column data types

### 5. Outlier Detection

The **Interquartile Range (IQR)** method was used to identify potential outliers in numerical columns.

Outliers were evaluated before deciding whether they should be retained or capped.

For example, unusually high values in the `Fare` column were investigated and handled using an appropriate capping strategy.

### 6. Data Type Correction

Column data types were checked and corrected where necessary.

Examples:

- `PassengerId` → String/Object
- `Age` → Numeric
- `Fare` → Float
- Categorical columns → Object

---

## 📊 Before vs After Data Quality

The project compares the dataset before and after cleaning using:

- Row count
- Missing value count
- Duplicate count
- Data types
- Data quality

This demonstrates the improvement achieved through the cleaning process.

---

## 📁 Project Files

### `Titanic_Data_Cleaning.ipynb`

Jupyter Notebook containing the complete data cleaning workflow.

### `train.csv`

Original Titanic dataset used for the analysis.

### `Titanic_Cleaned.csv`

Final cleaned and analysis-ready dataset.

---

## 🎯 Key Learning Outcomes

Through this project, I practiced:

- Data inspection using Pandas
- Missing value handling
- Duplicate detection and removal
- Data standardization
- Outlier detection using IQR
- Data type conversion
- Before-and-after data quality comparison
- Exporting cleaned datasets

---

## 🚀 Conclusion

The raw Titanic dataset was systematically cleaned and transformed into an analysis-ready dataset.

This project demonstrates practical data preprocessing skills that are essential for **Data Analyst and Machine Learning workflows**.

---

## 👨‍💻 Author

**Mahesh Nasarla**

B.Tech – Computer Science and Data Science
