# 🏪 Walmart Sales Data Analysis using SQL

## 📘 About
This project analyzes **Walmart's sales data** to identify **high-performing branches**, **top-selling products**, and understand **customer purchasing behavior**.  
The goal is to extract **key performance insights (KPIs)** that can help Walmart **optimize sales strategies** and improve profitability.

The dataset is sourced from the **Kaggle Walmart Sales Forecasting Competition**, containing sales transactions from Walmart branches located in **Mandalay**, **Yangon**, and **Naypyitaw**.

---

## 🎯 Purpose of the Project
The primary objective is to:
- Calculate **Key Performance Indicators (KPIs)** in Walmart’s sales.
- Explore factors influencing sales across different branches.
- Evaluate customer patterns, product performance, and payment preferences.
- Provide data-driven recommendations for improving business performance.

---

## 🧾 Dataset Information
**Database Name:** `conn_ex`  
**Table Name:** `walmartsalesdata`  
**Records:** ~1,000+ transactions (sample below)

| Column Name | Description |
|--------------|-------------|
| `Invoice_ID` | Unique identifier for each transaction |
| `Branch` | Branch code (A, B, C) |
| `City` | City where the branch is located |
| `Customer_type` | Type of customer (Member or Normal) |
| `Gender` | Gender of customer |
| `Product_line` | Product category sold |
| `Unit_price` | Price per unit |
| `Quantity` | Number of items purchased |
| `Tax 5%` | 5% tax applied |
| `Total` | Total amount (including tax) |
| `Date` | Transaction date |
| `Time` | Transaction time |
| `Payment` | Payment method (Cash, E-wallet, Credit card) |
| `cogs` | Cost of goods sold |
| `gross_margin_percentage` | Gross margin percentage |
| `gross_income` | Gross profit |
| `Rating` | Customer satisfaction rating |

---

## 🔍 Analysis Performed

### 🧩 1. Product Analysis
- Identify top-performing product lines.
- Compare sales volume and profitability across product categories.
- Find areas needing improvement based on sales and ratings.

### 💰 2. Sales Analysis
- Analyze sales trends over time.
- Compare revenue, profit, and total transactions.
- Measure sales performance by city, branch, and month.

### 👥 3. Customer Analysis
- Segment customers by type and gender.
- Analyze purchase patterns and ratings.
- Evaluate customer value and profitability contribution.

---

## 🧠 Business Questions & SQL Queries

1. Total number of transactions in the dataset.  
2. Total Revenue and Total Income.  
3. Total number of items sold.  
4. Average revenue per transaction.  
5. Average customer rating across all transactions.  
6. Total sales by each branch and city.  
7. Total sales and profit per product line.  
8. Sales contribution by each payment method.  
9. Sales and profit trends for **January, February, March**.  
10. Comparison of **weekend vs weekday** sales.  
11. Identification of **peak sales hours**.  
12. Total gross income by each branch.  
13. Top 5 highest sales transactions.  
14. Total sales and % contribution of each customer type.  
15. Sales and profit comparison by gender.  

---

## 📊 Key Insights

### 💵 Revenue & Transactions
- **Naypyitaw** recorded the **highest total revenue**, followed by **Yangon** and **Mandalay**.  
- **Average revenue per transaction** ≈ **USD 322.97**.  
- **Female customers** contributed more to overall sales and profit.  

### 🏬 Branch Performance
- **Branch C** generated the **highest sales**, while **Branch B** had the **lowest**.  

### 🛍️ Product Lines
- **Food & Beverages** and **Sports & Travel** lead in total sales.  
- These lines also received **higher average ratings**.  

### 👨‍👩‍👧 Customer Types
- **Members** spend slightly more per transaction than Normal customers.  
- Members also **rate their experience higher** on average.  

### 💳 Payment Methods
- **Cash** is the most popular payment method, followed by **E-wallet** and **Credit Card**.  
- Indicates **dominance of cash**, but **digital payment adoption is growing**.  

### ⏰ Time-based Trends
- **Peak sales hours:** 1:00 PM to 7:00 PM.  
- **Weekdays** outperform weekends in total sales.  

### ⭐ Customer Satisfaction
- Average customer rating: **6.9 – 7.5**.  
- **Mandalay** shows slightly lower ratings than other branches.  

---

## 📈 Conclusion

- **Naypyitaw** and **Branch C** are the **top revenue contributors**.  
- **Food & Beverages** and **Sports & Travel** are the most profitable categories.  
- **Cash** remains dominant, but encouraging **E-wallet/Credit Card** can improve convenience.  
- **January** had the **highest monthly sales**, followed by **March** and **February** — indicating **seasonal purchasing behavior**.  
- Walmart can boost underperforming branches through:
  - Targeted marketing
  - Discounts and promotions
  - Focusing on trending products and customer preferences  

> 📊 By implementing these insights, Walmart can **increase market share, enhance customer satisfaction**, and **maximize profit**.

---

## 🧰 Tools & Technologies Used
- **SQL (MySQL Workbench)** – for querying and analysis  
- **Database:** `conn_ex`  
- **Excel** – for dataset preview and data validation  
- **Kaggle Dataset:** Walmart Sales Forecasting Competition  

---

## 🚀 How to Run This Project

1. Install **MySQL Workbench** or any preferred SQL IDE.  
2. Create the database and table:
   ```sql
   CREATE DATABASE conn_ex;
   USE conn_ex;















