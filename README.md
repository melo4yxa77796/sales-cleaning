# sales-cleaning
# 🧹 Sales Data Cleaning and Preparation

This project focuses on cleaning and preparing sales transaction data to ensure its quality and reliability for future business analysis.

---

## 🎯 Project Objectives

- Identify and handle missing or null values.
- Detect and remove duplicate records.
- Correct inconsistent data types.
- Address unrealistic sales values (e.g., negative amounts).
- Create a clean dataset ready for analysis.

---

## 🛠 Technologies Used

- Python 3.12
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook
- Visual Studio Code

---

## 🔍 Cleaning Steps Performed

- Loaded the raw sales data from `sales_data.csv`.
- Checked for missing values and visualized them using a heatmap.
- Removed duplicate records to ensure data integrity.
- Corrected the data types, especially the `Sale Date` column.
- Calculated a new column `Total Sales` (Quantity × Unit Price).
- Removed entries with negative sales amounts.
- Exported the cleaned data into `cleaned_sales_data.csv`.

---

## 📈 Sample Visualization


### Total Sales by Product Category

The bar plot below shows the total sales distributed across different product categories.

![Total Sales by Category](https://github.com/melo4yxa77796/sales-cleaning/blob/main/Screenshot%202025-04-27%20at%2012.13.31.png)

*(Replace the link if you add your actual plot image!)*


## 📄 Files Included

- `sales_data.csv` — Raw sales data.
- `cleaned_sales_data.csv` — Cleaned and prepared dataset.
- `sales_cleaning.ipynb` — Jupyter Notebook with full cleaning process.
- `README.md` — Project description.

---

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/melo4yxa77796/sales-cleaning.git
