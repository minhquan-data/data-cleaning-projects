# data-cleaning-projects
Project làm sạch dữ liệu
# FIFA 21 Players Data Cleaning

This project focuses on cleaning and preprocessing the **FIFA 21 players dataset** using Python and pandas. The goal is to prepare the data for further analysis or modeling.

## 📘 Notebook

The main data cleaning process is performed in the notebook:
📄 `fifa21_data_cleaning.ipynb` 

## 📂 Dataset

- Dataset used: `players_21.csv`

## 🧹 Cleaning Tasks Performed

- Read the raw dataset into a pandas DataFrame
- Checked and handled missing values in columns such as `height_cm`, `weight_kg`
- Converted `joined` column to `datetime` format
- Extracted `year`, `month`, `day` from the `joined` column
- Converted monetary fields (`value_eur`, `wage_eur`) to numeric format, handling invalid/missing data
- Standardized data types for numerical columns
