# 🧹 Task 1: Data Cleaning and Preprocessing

## 📌 Objective
The goal of this task is to clean and prepare a raw dataset for further analysis by handling missing values, removing duplicates, standardizing inconsistent formats, and validating data types.

## 📊 Dataset
**Dataset Name**: [Customer Personality Analysis](https://www.kaggle.com/datasets/imakash3011/customer-personality-analysis)  
**Source**: Kaggle  
This dataset contains demographic and behavioral data of customers for targeted marketing campaigns.

## 🛠️ Tools Used
- Python 🐍
- Pandas (Data manipulation and preprocessing)
- Google Colab (Execution environment)

## 🧼 Cleaning Steps Performed

- ✔️ Identified and imputed missing values in the `income` column using the median.
- ✔️ Checked for and confirmed the absence of duplicate rows.
- ✔️ Renamed columns to lowercase and replaced spaces with underscores for consistency.
- ✔️ Converted the `dt_customer` column to `datetime` format.
- ✔️ Standardized categorical values:
  - Merged `"2n Cycle"` with `"Master"` in `education`
  - Replaced invalid `marital_status` entries like `"YOLO"`, `"Absurd"`, and `"Alone"` with `"Other"`
- ✔️ Validated and corrected data types:
  - Ensured numerical fields (e.g., `year_birth`, `income`, `kidhome`) were of proper numeric types.
  - Ensured date field was properly parsed as `datetime64[ns]`.

## 📁 Files Included

- `cleaned_customer_data.csv` – Final cleaned dataset
- `Elavate_Lab_Task_1.ipynb` – Google Colab notebook with code and documentation
- `README.md` – Task summary and context

## 📈 Outcome
The dataset is now clean, consistent, and ready for exploratory data analysis and modeling.  
**Final Dataset Shape**: `(2216, 29)`

## 🧠 Author
**Bhavesh Santoshkumar Tupe**  
Data Analyst Intern – Elevate Labs

---

