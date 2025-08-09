# SQL Data Analysis

This project contains SQL scripts designed to perform data analysis on sales and customer datasets within a Data Warehouse structure.  
The main goal is to generate reports and metrics that can be used in Business Intelligence (BI) scenarios.

---

## 📂 Project Structure
sql_data_analysis/
├── category_sales_contribution.sql # Category-wise total sales and percentage contribution
├── customer_metrics_report.sql # Customer metrics, age groups, and segmentation analysis
├── customer_segments_by_spending.sql # Customer segmentation based on spending behavior
├── monthly_running_sales.sql # Monthly and cumulative sales report
├── monthly_sales_report.sql # Monthly sales summary
├── product_price_segments.sql # Number of products by price range
├── yearly_product_performance.sql # Yearly performance analysis of products
└── datasets/ # Datasets used in the analysis

---
## 📊 Analysis & Reports

### **1. Sales Analysis**
- Monthly total sales
- Cumulative sales trends
- Sales contribution by category
- Product distribution by price segments

### **2. Customer Analysis**
- Customer distribution by age group
- VIP / Regular / New segmentation
- Average Order Value (AOV) and average monthly spend

### **3. Product Performance Analysis**
- Year-over-year sales changes
- Above/Below average sales classification
- Annual performance comparisons

---

## 📂 Dataset
- **Folder**: `datasets/`
- **Example Data**: Sales, customer, and product tables
- **Schema**:
  - **fact_sales**: order details (date, product, customer, sales amount)
  - **dim_products**: product details (category, price, name)
  - **dim_customers**: customer details (age, name, customer number)

> **Note:** No real data is used; analyses are performed on sample or synthetic datasets.

---

## 🚀 Usage
1. Open the `.sql` files in SQL Server Management Studio (SSMS) or a compatible SQL editor.
2. Run the queries on the respective database schema.
3. Use the results for reporting, data visualization, or Business Intelligence dashboards.

