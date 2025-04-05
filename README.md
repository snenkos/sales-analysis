# Sales Project Analysis: Supply Chain, Financial & Sales Insights

## Overview
This project provides a comprehensive analysis of sales data to derive actionable insights into supply chain performance, inventory optimization, and financial profitability. The analysis covers:
- **Data Quality & Exploration:** Reviewing the dataset for missing values and understanding its structure.
- **Supplier Performance:** Assessing suppliers based on lead time consistency, stock levels, and overall sales.
- **Sales & Lead Time Analysis:** Investigating the relationship between lead times and sales quantity.
- **Inventory Optimization:** Estimating daily sales and reorder points to prevent stockouts.
- **Financial Analysis:** Calculating profit margins to identify the most profitable products.

## Data
The project uses a cleaned sales dataset stored in an Excel file (`cleaned_sales_project.xlsx`) that includes the following key columns:
- Date, Title, Category, Supplier
- Sales Quantity, Original Price, Discount %, Final Price
- Unit Cost, Revenue, Profit
- Lead Time (days), Stock Level

## Key Analyses

1. **Data Exploration:**  
   - Import libraries: pandas, numpy, matplotlib, and seaborn.
   - Load and inspect the Excel dataset.
   - Identify missing values in key columns (e.g., `Original Price`, `Final Price`).

2. **Supply Chain Analytics:**  
   - Group data by supplier to calculate performance metrics such as mean and standard deviation of lead times, stock levels, and total sales quantity.
   - Rank suppliers based on lead time variability.

3. **Lead Time Impact on Sales:**  
   - Compute the correlation between lead time and sales quantity, revealing a slight negative relationship.

4. **Inventory Optimization:**  
   - Calculate average daily sales and estimated reorder points.
   - Identify products at risk of stockouts when the average stock level is below the reorder point.
   - Visualize the top 10 products with the highest stock gaps.

5. **Financial Analysis:**  
   - Calculate profit per unit and profit margin percentage.
   - Identify and visualize the top 10 most profitable products based on average profit margins.

## Requirements
- **Python 3.x**

### Required Libraries
- pandas
- numpy
- matplotlib
- seaborn

Install the required libraries using pip:
```bash
pip install pandas numpy matplotlib seaborn
