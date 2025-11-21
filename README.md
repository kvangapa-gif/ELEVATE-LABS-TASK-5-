# ELEVATE-LABS-TASK-5-

SALES DATA ANALYSIS REPORT — README
Overview
This Python script produces a comprehensive analysis of DMart sales data from a CSV file, generates insightful visualizations, and compiles everything into an Excel report for easy sharing and review. The process is automated end-to-end—from data cleaning to chart generation and reporting—so even non-specialists can use it with minimal effort .

Features
Loads DMart sales data from CSV and performs essential preprocessing.

Visualizes monthly sales trends, customer mix, product category sales, and highlights heatmap relationships.

Automatically creates and saves an Excel report featuring all visualizations and summary insights .

Prerequisites
Python 3.7+

Required packages: pandas, matplotlib, seaborn, openpyxl

Your CSV data file (must include Date, Total, CustomerType, and ProductCategory columns)

To install dependencies, run:

bash
pip install pandas matplotlib seaborn openpyxl
Usage Instructions
Prepare your CSV: Place the DMart sales file at the location /content/DMart_sample_data.csv.
Modify the file_path variable in the script if your data is elsewhere .

Run the script: All steps are automatic, including data loading, processing, visualization, and Excel report creation.

Output files:

Individual charts:
/content/monthly_sales_trend.png
/content/customer_pie.png
/content/sales_heatmap.png
/content/category_bar_sorted.png

Excel report:
/content/Sales_Report.xlsx (with embedded images and insights)

Step-by-Step Breakdown
1. Data Loading and Processing
Reads CSV data into a pandas DataFrame.

Converts the date column to standard format and adds month grouping.

Prepares total sales as a float for accuracy.

Ensures that all output paths exist .

2. Visualizations
Monthly Sales Trend: Line chart shows total sales evolution over months, revealing seasonal spikes.

Customer Type Pie Chart: Displays proportions for each customer category in sales.

Sales Heatmap: Illustrates product category performance across months for deeper pattern discovery.

Top Categories Bar Chart: Ranks products by total sales for quick decision making .

3. Excel Report
All charts and their insights are inserted into a single-sheet Excel file.

Images are positioned and accompanied by textual observations for context.

The final report is saved in /content/ for easy access .

Customization Tips
Data Path: Change the file_path variable if your data is stored elsewhere.

Chart Styles: You may modify color maps or chart aesthetics to match your organization's branding.

Excel Formatting: The code uses default openpyxl styling, but you can enhance formatting for enterprise use .
