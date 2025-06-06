# Sales Data Analysis & Dashboard using Power BI

## Task

The objective of this project is to analyze a sales dataset, clean and preprocess it using Python, enhance it for time-based insights, and create an interactive dashboard in Power BI to visualize sales and profit trends across different regions and categories.

---

## Files Included

| File Name                           | Description |
|------------------------------------|-------------|
| `Data_Cleaning.ipynb`              | Jupyter Notebook used to clean the original dataset using Python (handled nulls, fixed data types, etc.) |
| `Cleaned_Sales_By_Region.csv`      | Final cleaned dataset ready for use in Power BI |
| `Dashboard.pdf`                    | Exported view of the Power BI dashboard showing various sales and profit insights |
| `INSIGHTS OF SALES DASHBOARD.pdf` | Contains a summary of key insights derived from the dashboard visuals |

---

## ⚙How It Was Done

1. **Data Cleaning**  
   Performed using Python in `Data_Cleaning.ipynb`:
   - Removed missing values  
   - Converted date columns to datetime format  
   - Validated numerical columns like `sales`, `profit`, and `quantity`

2. **Data Enhancement**  
   - A new `month-year` column was created using Excel for time-series analysis  
   - Final dataset saved as `Cleaned_Sales_By_Region.csv`

3. **Dashboard Creation**  
   - Built in Power BI using the cleaned dataset  
   - Exported as `Dashboard.pdf` for sharing  
   - Visuals include:  
     - Line chart for monthly sales trend  
     - Bar chart of sales/profit by category  
     - Map and pie chart of sales by region  
     - KPI cards for total sales and total profit

4. **Insight Extraction**  
   - Key observations were written in `INSIGHTS OF SALES DASHBOARD.txt`  
   - Includes trends, top-performing categories, and regional analysis

---

## Summary

This project showcases the complete data analysis pipeline:  
**Data Cleaning → Data Enhancement → Visualization → Insight Extraction**

