# Sales and Temperature Data Analysis using Pandas

# Overview
This project demonstrates data cleaning, transformation, and analysis using Python's Pandas and Matplotlib libraries. 
We analyze two real-world datasets: Walmart sales data and global temperature time series, focusing on data quality, statistical analysis, and visualization.

# Objectives
- Practice data cleaning: remove duplicates, handle outliers, fix inconsistent casing, trim spaces, and standardize date formats.
- Extract and filter data for specific stores, departments, and countries.
- Perform data transformation and statistical analysis.
- Visualize trends and relationships using plots.
- (Bonus) Explore the correlation between sales and temperature.

# Datasets
1. **Walmart Sales Data**: Columns include `Date`, `Store`, `Department`, `Sales`, `Quantity`.
2. **Global Temperature Data**: Columns include `Date`, `Global_Temperature`, `City`, `Country`.

# Requirements
- Python 3.x
- pandas
- matplotlib

# Key Tasks and Methods
1. Data Importing
   - Load both datasets into Pandas DataFrames.

2. Data Cleaning
   - Remove duplicate rows.
   - Handle outliers in `Sales` and `Global_Temperature` using quantile capping.
   - Standardize casing in `City` and `Country` columns.
   - Trim extra spaces from city and country names.
   - Convert `Date` columns to datetime objects and sort data by date.

3. Data Extraction and Filtering
   - Extract data for a particular store (e.g., Store 2) and department (e.g., Department 4) from Walmart data.
   - (Optional) Filter global temperature data for a specific country.

4. Data Transformation
   - Add a `Revenue` column to Walmart data, calculated as `Sales * Quantity`.

5. Statistical Analysis
   - Compute summary statistics (mean, median, std, etc.) for `Sales` and `Revenue` for filtered Walmart data.
   - Find highest and lowest global temperatures for a selected country.

6. Data Visualization
   - Create line plots showing sales trends for selected store/department.
   - Create line plots for monthly average temperature for a selected country.

7. Bonus Analysis
   - Merge Walmart sales and global temperature data on `Date` to explore potential correlations.

# Deliverables
- A Jupyter Notebook containing all code, comments, and plots.
- A report summarizing the analysis, findings, and visualizations.

# Evaluation Criteria
- **Code Quality**: Well-organized, readable, and commented code.
- **Data Manipulation**: Effective data cleaning, extraction, and transformation.
- **Statistical Analysis**: Sound and well-explained statistics.
- **Data Visualization**: Clear, well-labeled, and insightful plots.
- **Report**: Thorough summary and actionable conclusions.

# How to Use
1. Ensure Python 3.x and required libraries are installed.
2. Place the datasets (`task_walmart_sales_data.csv` and `task_global_temperature_data.csv`) in the project directory.
3. Open and run the Jupyter Notebook to perform the analysis.
4. Review the generated plots and report for insights.

# Summary
This project showcases practical data science skills, including data cleaning, transformation, statistical analysis, and visualization. 
By working with real-world sales and temperature data, it provides insights into retail performance and environmental trends, and demonstrates how to prepare data for further analytics or machine learning.

# Author
Seif Hossam Eldeen
