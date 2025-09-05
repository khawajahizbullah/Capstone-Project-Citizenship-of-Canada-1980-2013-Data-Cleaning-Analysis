# 🧹 Capstone Project: Citizenship of Canada (1980–2013) Data Cleaning & Analysis  

## 📖 Project Overview  
This project focuses on cleaning and preparing the dataset **"Citizenship of Canada by 2013.xlsx"**, which contains immigration data from **1980 to 2013**.  
The dataset originally had **218 rows and 43 columns**, with challenges like:  
- Missing values  
- Zeros representing missing data  
- Infinite values  
- Negative values in certain year columns  

The goal of this project is to create a **clean, analysis-ready dataset** that can be used for further **data analysis or visualization.**  

---

## 🛠️ Tools & Libraries  
- **Python**  
- **Pandas** → Data manipulation & cleaning  
- **NumPy** → Numerical operations  

---

## ⚡ Data Cleaning Steps Implemented  
1. **Loaded Excel Dataset**  
2. **Detected and handled missing values**  
   - Converted invalid/zero entries into NaN  
   - Replaced NaN with column-wise means  
3. **Handled infinite values**  
   - Replaced `inf` and `-inf` with NaN  
4. **Handled negative values**  
   - Replaced negatives with column-wise mean of valid values  
5. **Exported a cleaned dataset** → `Cleaned Citizenship of Canada by 2013 New.xlsx`  

---

## 📂 Files in Repository  
- `Citizenship of Canada by 2013.xlsx` → Original dataset  
- `Citizenship_of_Canada_by_2013.ipynb` → Python script for data cleaning  
- `Cleaned Citizenship of Canada by 2013 New.xlsx` → Final cleaned dataset  

---
