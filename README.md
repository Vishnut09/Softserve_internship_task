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
Beginner-level EDA using pandas: load dataset, check shape, column names, and preview rows.
## 📂 Dataset
Retail Sales Dataset (Sample Sales Data)
Source: https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets

##  Day 3 – Handling Missing Data
- Checked for missing values using `isna().sum()`
- Applied the following methods:
- Dropped rows with all-null values (if any)
- Imputed missing values in numeric/categorical columns
- Cleaned dataset saved as `/content/StressLevelDataset.csv`

- ##  Day 4 – Fix Data Types & Remove Duplicates
- Converted date columns to datetime format using `pd.to_datetime()`
- Ensured numeric columns are in correct type using `pd.to_numeric()`
- Removed duplicate records using `drop_duplicates()`
- Saved updated dataset as `/content/StressLevelDataset.csv`

## 📊 Day 5 – Data Normalization & Scaling
- Identified numerical columns in the dataset.
- Applied `MinMaxScaler` to normalize values between 0 and 1.
- Saved the preprocessed dataset as
`data/preprocessed_data.csv`.
- All steps are documented in `preprocessing.ipynb`.

## 📤 Day 6 – Export Data for Power BI
- Loaded preprocessed dataset from Day 5.
- Verified data integrity and structure.
- Exported final dataset as `/content/final_data_for_powerbi.csv` for visualization in Power BI.

- visualization_plan.md


# Day 7 – Data Visualization Plan for Power BI

## 📈 Dashboard Objective
To explore student stress levels and the factors that affect them, such as sleep, academic pressure, and mental health history.

## 🔑 KPIs to Display
- Average Stress Level
- Stress Level by Gender
- Sleep Quality vs Stress Level
- Academic Pressure vs Stress Level
- Mental Health History Distribution

## 📊 Planned Visuals

| KPI                             | Chart Type    | Description                                                   |
|----------------------------------|---------------|---------------------------------------------------------------|
| Average Stress Level            | Card          | Show overall average stress from all students                 |
| Stress by Gender                | Bar Chart     | Compare average stress across genders                         |
| Sleep Quality vs Stress         | Scatter Plot  | Show relationship between sleep and stress                    |
| Academic Pressure vs Stress     | Line Chart    | Track how pressure affects stress                             |
| Mental Health History Breakdown | Donut Chart   | Show how many students have or don't have mental health issues |

 1. Which gender reports higher stress levels?

Answer: By grouping average stress level by gender (using a bar chart), we can identify whether male or female students report higher stress on average.

 2. Is there a correlation between sleep quality and stress level?

Answer: A scatter plot or line chart can show if poor sleep quality is associated with high stress — indicating a possible inverse relationship.

 3. Do students with a history of mental health issues have higher stress levels?

Answer: Comparing the stress levels between students who answered "Yes" and "No" to having a mental health history can highlight a significant difference.

 4. How does academic pressure affect student stress?

Answer: Plotting academic pressure against stress level can help show if increasing academic demands directly increase stress levels.

 5. What percentage of students receive support during stress?

Answer: A pie chart showing “Got Support” vs “Didn’t Get Support” gives a quick view of whether students have access to help when stressed.

 6. What is the average stress level among all students?

Answer: This is a KPI that can be displayed as a Card in Power BI showing the mean stress score.

## ⚙️ Next Step
Use this plan to create a Power BI dashboard tomorrow using `final_data_for_powerbi.csv`.




## Day 9 – Power BI Data Connection
- Loaded dataset `final_data_for_powerbi.csv` into Power BI.
- Verified the data model and field types.
- Saved the Power BI file as `data_model.pbix` for visualization in Day 10

























## Data Preprocessing Summary (Day 8)
Below are the steps performed during the preprocessing
pipeline:
1. **Handled Missing Values (Day 3):**
- Used `isna().sum()` to identify missing values.
- Imputed missing numerical columns with mean.
- Filled missing categorical values with
`'Unknown'`.
2. **Fixed Data Types & Removed Duplicates (Day 4):**
- Converted date columns using `pd.to_datetime()`.
- Converted object columns to numeric types using
`pd.to_numeric()`.
- Removed duplicate rows using `drop_duplicates()`.
3. **Applied Feature Scaling (Day 5):**
- Applied `MinMaxScaler` from scikit-learn to
normalize numeric features.
- Saved results as `preprocessed_data.csv`.
4. **Exported Clean Data for Power BI (Day 6):**
- Verified final structure of data.
- Exported dataset for visualization as
`final_data_for_powerbi.csv`.
5. **Planned Visualizations (Day 7):**
- Identified key KPIs and suitable chart types.
- Documented layout in `visualization_plan.md`.
- 
➡️ These steps ensure the dataset is clean,
standardized, and ready for visualization and modeling.











https://www.kaggle.com/datasets/mdsultanulislamovi/student-stress-monitoring-datasets
