# Softserve_internship_task

# Day 1 – Analytics Setup
## 📘 Objective
To set up the environment and select a dataset for
future data analytics tasks.
## 🛠 Tools Installed
- Anaconda (Python, Jupyter Notebook)
- Power BI Desktop
## 📂 Dataset Chosen
**Dataset:** Student Stress monitoring dataset
**Source:** https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets
## 🚀 Next Steps
- Load the dataset using pandas
- Perform basic EDA

# EDA Task - 19 Aug
## 📘 Objective
Beginner-level EDA using pandas: load dataset, check shape, column names, and
preview rows.
## 📂 Dataset
Retail Sales Dataset (Sample Sales Data)
Source: https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets

## 🧹 Day 3 – Handling Missing Data
- Checked for missing values using `isna().sum()`
- Applied the following methods:
- Dropped rows with all-null values (if any)
- Imputed missing values in numeric/categorical
columns
- Cleaned dataset saved as `/content/StressLevelDataset.csv`

- ## 🔄 Day 4 – Fix Data Types & Remove Duplicates
- Converted date columns to datetime format using
`pd.to_datetime()`
- Ensured numeric columns are in correct type using
`pd.to_numeric()`
- Removed duplicate records using `drop_duplicates()`
- Saved updated dataset as `/content/StressLevelDataset.csv`

## 📊 Day 5 – Data Normalization & Scaling
- Identified numerical columns in the dataset.
- Applied `MinMaxScaler` to normalize values between 0
and 1.
- Saved the preprocessed dataset as
`data/preprocessed_data.csv`.
- All steps are documented in `preprocessing.ipynb`.

## 📤 Day 6 – Export Data for Power BI
- Loaded preprocessed dataset from Day 5.
- Verified data integrity and structure.
- Exported final dataset as `/content/final_data_for_powerbi.csv` for visualization in Power BI.









































https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets
