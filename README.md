# \# SQL Data Analysis

# 

# This project contains SQL scripts designed to perform data analysis on sales and customer datasets within a Data Warehouse structure.  

# The main goal is to generate reports and metrics that can be used in Business Intelligence (BI) scenarios.

# 

# \## 📂 Project Structure

# sql\_data\_analysis/

# ├── category\_sales\_contribution.sql # Category-wise total sales and percentage contribution

# ├── customer\_metrics\_report.sql # Customer metrics, age groups, and segmentation analysis

# ├── customer\_segments\_by\_spending.sql # Customer segmentation based on spending behavior

# ├── monthly\_running\_sales.sql # Monthly and cumulative sales report

# ├── monthly\_sales\_report.sql # Monthly sales summary

# ├── product\_price\_segments.sql # Number of products by price range

# ├── yearly\_product\_performance.sql # Yearly performance analysis of products

# └── datasets/ # Datasets used in the analysis

# 



# 

# \## 📊 Analysis \& Reports

# 

# 1\. \*\*Sales Analysis\*\*

# &nbsp;  - Monthly total sales

# &nbsp;  - Cumulative sales trends

# &nbsp;  - Sales contribution by category

# &nbsp;  - Product distribution by price segments

# 

# 2\. \*\*Customer Analysis\*\*

# &nbsp;  - Customer distribution by age group

# &nbsp;  - VIP / Regular / New segmentation

# &nbsp;  - Average Order Value (AOV) and average monthly spend

# 

# 3\. \*\*Product Performance Analysis\*\*

# &nbsp;  - Year-over-year sales changes

# &nbsp;  - Above/Below average sales classification

# &nbsp;  - Annual performance comparisons

# 

# \## 📂 Dataset

# \- \*\*Folder\*\*: `datasets/`

# \- \*\*Example Data\*\*: Sales, customer, and product tables

# \- \*\*Schema\*\*:

# &nbsp; - \*\*fact\_sales\*\*: order details (date, product, customer, sales amount)

# &nbsp; - \*\*dim\_products\*\*: product details (category, price, name)

# &nbsp; - \*\*dim\_customers\*\*: customer details (age, name, customer number)

# 

# > Note: No real data is used; analyses are performed on sample or synthetic datasets.

# 

# \## 🚀 Usage

# 1\. Open the `.sql` files in SQL Server Management Studio (SSMS) or a compatible SQL editor.

# 2\. Run the queries on the respective database schema.

# 3\. Use the results for reporting, data visualization, or Business Intelligence dashboards.

