# SQL Exploratory Data Analysis (EDA)

## 📌 Project Overview
This project is an **Exploratory Data Analysis (EDA)** using **SQL**, applied to a sales database with a focus on **insights for marketing decision-making**.

The goal was to: 

- understand the database structure, 
- explore dimensions and business metrics, 
- calculate KPIs, 
- identify performance patterns related to **products, customers, and sales**.

This project was developed as part of a **SQL course** using simulated data.

---

## 🛠️ Tools & Concepts Used
- SQL
- Relational Databases
- Data Profiling
- Aggregations (`SUM`, `AVG`, `COUNT`)
- Subqueries
- Joins
- Window Functions (`ROW_NUMBER`)
- KPI Analysis
- Exploration of Dimensions and Measures

---

## 🗂️ Database Structure
The database follows a relational model with fact and dimension tables:

- **fact_sales**: transactional sales data (orders, quantity, revenue)  
- **dim_customers**: customer demographics (country, gender, birthdate)  
- **dim_products**: product information (category, subcategory, cost)  

---

## 🔍 Analyses Performed

### 1️⃣ Database Exploration
- Identified tables and columns using `INFORMATION_SCHEMA`  
- Understood table relationships and data types  

---

### 2️⃣ Dimension Exploration
- Identified unique values in dimensions such as:  
  - Country  
  - Product category and subcategory  
  - Product name  
- Analyzed data segmentation  

---

### 3️⃣ Date Analysis
- Identified first and last order dates  
- Calculated total sales period  
- Determined youngest and oldest customers  

---

### 4️⃣ Business Metrics and KPIs
- Calculated key performance indicators:  
  - Total revenue  
  - Total quantity sold  
  - Average price  
  - Total orders (distinct and overall)  
  - Total products  
  - Total customers  
  - Customers who placed orders  

- Generated a **consolidated KPI report** using `UNION ALL`.

---

### 5️⃣ Magnitude Analysis
- Total customers by country and gender  
- Total products by category  
- Average cost per category  
- Total revenue per category  
- Revenue per customer  
- Distribution of sold items by country  

---

### 6️⃣ Ranking and Performance Analysis
- Top 5 products by revenue  
- 5 lowest-performing products by sales  
- Top 10 customers by revenue  
- 3 customers with the fewest orders  
- Used **window functions** for ranking products  

---

## 📊 Key Learnings
- Understanding how sales and customer data support marketing decisions  
- Identifying top-performing products and customers contributing most to revenue  
- Analyzing performance by category, region, and customer profile  
- Practicing SQL with a **business-oriented perspective**, not just technical  

---

## 📎 Notes
- Academic project using simulated data  
- Focused on **SQL logic, exploratory analysis, and generating business insights**  

---

## 🚀 Skills Demonstrated
- SQL exploratory data analysis  
- Analytical thinking applied to marketing and sales  
- KPI creation and reporting  
- Data interpretation to support decision-making  
