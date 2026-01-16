# Task 2: Data Cleaning & Missing Value Handling

This task focuses on understanding, identifying, and handling missing values in real-world datasets using Python. The goal is to validate data quality and apply appropriate preprocessing techniques where required.

## Datasets Used

### 1. House Prices Dataset (train.csv)
Source: Kaggle – House Prices: Advanced Regression Techniques  

This dataset contains both numerical and categorical features with several missing values, making it suitable for practicing data cleaning techniques.

Steps performed:
- Loaded the dataset and inspected its structure
- Checked missing values using `isnull().sum()`
- Visualized missing value distribution
- Applied median imputation for numerical columns
- Applied mode imputation for categorical columns
- Removed columns with extremely high missing values using a threshold
- Compared dataset shape before and after cleaning
- Saved the cleaned dataset for further use

Outcome:  
The dataset was successfully cleaned and prepared for machine learning tasks.

### 2. Medical Appointment No Shows Dataset (KaggleV2-May-2016.csv)
Source: Public Medical Appointment Dataset  

This dataset represents real-world healthcare appointment data.

Steps performed:
- Loaded the dataset and examined data types
- Checked for missing values using `isnull().sum()`
- Validated the dataset using `info()` and `shape`
- Visualized missing value counts

Observation:  
No missing values were found in the dataset. Therefore, no imputation or column removal was required.

Outcome:  
The dataset was validated and confirmed to be clean, maintaining full data integrity.

## Conclusion
Through this task, hands-on experience was gained in:
- Identifying missing values
- Making data-driven decisions for cleaning
- Applying appropriate preprocessing techniques
- Validating dataset quality before model building

Both datasets are now ready for further analysis or machine learning workflows.
