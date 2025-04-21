# Sales_data_cleaning_and_preprocessing

This project is about cleaning a messy sales dataset using Python and Pandas.  
The raw data had problems like duplicate rows, extra spaces, missing values, and inconsistent date formats.  
I cleaned the data step by step and saved the final version as a new CSV file.
**encoding='ISO-8859-1'** Also called Latin-1, it supports a wider range of characters that are
commonly found in business or sales datasets — especially ones exported from Excel or older systems.


---
##  What I Did (Step-by-Step)
1. **Loaded the dataset** using Pandas with the correct encoding.
2. **Removed extra spaces** from column names.
3. **Removed duplicate rows** from the data.
4. **Formatted the 'orderdate' column** to have a proper date format.
5. **Removed extra spaces** from all text (string) values in the dataset.
6. **Replaced all missing values** with the word `'Unknown'`.
7. **Saved** the cleaned dataset to a new CSV file called `sales_data_cleaned.csv`.
---
## 🎯 Why Data Cleaning Is Important
Cleaning data is an essential first step in any data analysis , 
Here's why it's so important:

- ✅ **Accurate results**: Dirty data can lead to wrong insights and decisions.
- ✅ **Better performance**: Clean data helps dashboards and models run faster and more efficiently.
- ✅ **Professional reporting**: Clean data looks more presentable and is easier to work with.
- ✅ **Avoid errors**: Duplicate and missing values often cause errors in analysis or charts.
- ✅ **Improved trust**: Stakeholders and clients are more likely to trust clean, consistent data.
---
## Files Included
- `sales_data_sample(in).csv`: The original messy sales data
- `clean_sales_data.py`: Python code used for cleaning the dataset
- `sales_data_cleaned.csv`: The final cleaned version of the dataset
  ---
##  Tools Used

- Python 🐍
- Pandas 📊
- Jupyter Notebook 
---
## ✅ Outcome
The cleaned dataset is now ready for:

- Data analysis (exploring sales trends)
- Dashboard creation (in Power BI or Tableau)
- Building machine learning models
- Sharing with teams or managers without issues
---

