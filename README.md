# athletic_sales_analysis

### ChatGPT was used in the assistance of the code and readme file

## Overview
This project analyzes two years of sales data for athletic wear across the United States. The objective is to provide insights into sales performance by region, state, city, and retailer, as well as to identify patterns in women's athletic footwear sales.

The analysis includes:
- Identifying regions with the highest sales and products sold.
- Highlighting top-performing retailers.
- Analyzing daily and weekly sales trends for women's athletic footwear.

## Objectives
1. **Combine and Clean Data**:
   - Merge datasets from 2020 and 2021.
   - Clean and prepare the data for analysis.
2. **Analyze Regional Performance**:
   - Determine which regions sold the most products.
   - Identify regions with the highest total sales.
3. **Retailer Analysis**:
   - Find the top retailers with the greatest total sales.
   - Identify retailers that sold the most women's athletic footwear.
4. **Trend Analysis**:
   - Determine the days with the highest sales for women's athletic footwear.
   - Identify the weeks with the highest sales for women's athletic footwear.

## Files
- `athletic_sales_2020.csv`: Sales data for the year 2020.
- `athletic_sales_2021.csv`: Sales data for the year 2021.
- `athletic_sales_analysis.ipynb`: Jupyter Notebook containing the full analysis and results.

## Methodology
### Combine and Clean the Data
- Imported and combined the 2020 and 2021 datasets.
- Checked for null values and cleaned the data as necessary.
- Converted `invoice_date` column to a datetime data type.

### Regional Analysis
- Used `groupby` and `pivot_table` to analyze sales and products sold by `region`, `state`, and `city`.
- Aggregated `units_sold` and `total_sales` columns to identify top-performing regions.

### Retailer Analysis
- Filtered and grouped data to analyze retailer performance.
- Identified the top retailers based on total sales and sales of women's athletic footwear.

### Trend Analysis
- Created a pivot table to analyze daily and weekly sales trends for women's athletic footwear.
- Resampled data into daily and weekly bins to identify peak sales periods.

## Results
1. **Top Regions**:
   - Regions with the highest number of products sold and total sales were identified, along with their states and cities.
2. **Top Retailers**:
   - Retailers with the greatest total sales and women's athletic footwear sales were highlighted.
3. **Sales Trends**:
   - The top 10 days and weeks with the highest sales for women's athletic footwear were determined.

## How to Run the Analysis
1. Clone this repository to your local machine:
   ```bash
   git clone <repository_url>
