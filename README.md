🧹 Titanic Dataset – Data Cleaning Project
📌 Project Overview

This project focuses on cleaning and preprocessing real-world data using the Titanic dataset from Kaggle.
The objective is to convert raw, unstructured data into a clean, consistent, and analysis-ready dataset suitable for data analysis, visualization, and machine learning tasks.

📂 Dataset Information

Source: Kaggle – Titanic: Machine Learning from Disaster

File Used: train.csv

Initial Records: 891 rows, 12 columns

The dataset contains common data quality issues such as:

Missing values

Inconsistent categorical data

Irrelevant columns

Outliers

🛠 Tools & Technologies

Programming Language: Python

Primary Library: Pandas

Environment: Jupyter Notebook / VS Code

🧪 Data Cleaning Workflow
1️⃣ Data Inspection

Examined dataset structure, data types, and summary statistics

Identified missing values and inconsistent columns

2️⃣ Column Name Standardization

Removed extra spaces

Converted column names to lowercase

Ensured consistent naming for easier analysis

3️⃣ Handling Missing Values

Age: Filled using the median to reduce outlier impact

Embarked: Filled using the mode (most frequent category)

Cabin: Removed due to excessive missing values

4️⃣ Removing Irrelevant Columns

Dropped identifier and text-based columns that do not add analytical value

5️⃣ Duplicate Handling

Checked for duplicate records

Removed duplicates to maintain data integrity

6️⃣ Data Type Correction

Converted categorical columns to appropriate data types

Ensured numerical columns were correctly formatted

7️⃣ Outlier Treatment

Applied the Interquartile Range (IQR) method on fare values

Removed extreme values to prevent skewed analysis

8️⃣ Encoding Categorical Variables

Converted categorical features into numerical format using one-hot encoding

Prepared the dataset for machine learning models

9️⃣ Final Validation

Verified absence of missing values

Rechecked data types and distributions

Ensured dataset consistency and reliability

💾 Final Output

Cleaned Dataset: titanic_cleaned.csv

The dataset is fully prepared for:

Exploratory Data Analysis (EDA)

Power BI / Tableau dashboards

Machine Learning model training

🎯 Key Learnings

Importance of data inspection before cleaning

Choosing appropriate strategies for missing values

Handling outliers using statistical methods

Preparing categorical data for modeling

📌 Use Cases

Beginner to intermediate Data Analytics projects

Machine Learning preprocessing pipelines

Portfolio / Resume project demonstration

📎 Dataset Source

Kaggle – Titanic: Machine Learning from Disaster
