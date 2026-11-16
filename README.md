# 📊 Interactive Data Cleaning & Feature Engineering Pipeline

A Python-based interactive data analysis pipeline built using Pandas that simplifies dataset exploration, data cleaning, preprocessing, and feature engineering.

The project allows users to load CSV and Excel datasets, inspect data quality, handle missing values, standardize data types, and create new features through an interactive, menu-driven approach.

## 🚀 Features

### 1. Data Loading
- Load CSV datasets using Pandas.
- Load Excel (`.xlsx`) datasets.
- Read multiple sheets from Excel workbooks.
- Identify available CSV and Excel files in a directory.

### 2. Data Profiling
Analyze datasets before performing data cleaning.

- Dataset information and column data types.
- Total duplicate records.
- Missing values and their percentages.
- Value counts of categorical columns.
- Statistical summaries of numerical columns.

### 3. Data Cleaning

**Datatype Conversion**
- Convert columns into Float.
- Convert columns into Datetime.
- Handle invalid conversions using error handling.

**Missing Value Handling**

Choose from multiple techniques:

| Method | Description |
|---|---|
| Mean | Replace missing numerical values with the mean |
| Median | Replace missing values with the median |
| Mode | Replace missing values with the most frequent value |
| Custom Value | Replace missing values with a user-defined value |
| Forward Fill | Fill missing values using the previous record |
| Backward Fill | Fill missing values using the next record |
| Drop | Remove rows containing missing values |

### 4. Feature Engineering

Create new columns using different transformation techniques.

**Column Concatenation**
- Combine two existing columns.
- Add a custom separator.
- Generate a new column.

**Datetime Feature Extraction**
- Year
- Month
- Day
- Day Name
- Hour
- Minute
- Weekend Identification

**Conditional Column Creation**
Create new columns based on conditions:
- Greater Than
- Less Than
- Equal To
- Between

**Arithmetic Operations**
Perform calculations between two numerical columns:
- Addition (+)
- Subtraction (-)
- Multiplication (*)
- Division (/)

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## 🎯 Project Objectives

- Reduce repetitive manual data preparation.
- Simplify data exploration and quality assessment.
- Provide multiple missing-value treatment techniques.
- Make feature engineering easier and more interactive.
- Prepare datasets for further data analysis and machine learning tasks.

## 🔮 Future Improvements

- Automated duplicate removal.
- Statistical outlier detection.
- Automated data quality reports.
- Support for JSON and SQL databases.
- Export cleaned datasets directly to CSV and Excel.
- Streamlit-based interactive dashboard.

## 👨‍💻 Author

**Yuvraj Yadav**

B.Tech in Computer Science Engineering

Interested in Data Analytics, Data Science, Python, and Machine Learning.

- GitHub: https://github.com/YOUR-USERNAME
- LinkedIn: https://www.linkedin.com/

---

⭐ If you find this project useful, consider giving it a star!
