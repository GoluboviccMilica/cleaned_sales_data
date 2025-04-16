# cleaned_sales_data
Cleaned and prepared raw Excel data using pandas in Python
# Excel Data Cleaning Project

This project demonstrates a realistic data cleaning pipeline using Python and pandas.  
The dataset was intentionally messy and included common real-world issues like:
- Inconsistent capitalization
- Extra whitespace
- Duplicate rows
- Missing values
- Mixed date formats

## What Was Cleaned
- Standardized customer names (e.g. `" milica golubovic "` → `"Milica Golubovic"`)
- Unified region names (e.g. `"south"` → `"South"`)
- Removed exact duplicate rows
- Filled missing values:
  - `Units Sold` → 0
  - `Unit Price` → column median
- Converted mixed-format dates into proper datetime format
- Created a new column: `Total Sales` = `Units Sold * Unit Price`

## Files Included
- `messy_sales_data.xlsx` – Raw uncleaned file
- `cleaned_sales_data.xlsx` – Final cleaned version
- `data_cleaning.ipynb` – Jupyter Notebook with full cleaning pipeline

## Tools & Libraries
- Python 3.13
- pandas
- openpyxl
- Jupyter Notebook

## Key Takeaway
This notebook simulates the kind of repetitive, high-impact work data analysts do:  
Cleaning and transforming raw business data into a consistent, analysis-ready format.

---

*Created by Milica Golubović as part of her data analyst portfolio.*
