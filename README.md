# Sales-Analytics-SQL
End-to-end SQL project analyzing a retail dataset using joins, aggregations, CTEs, and window functions to extract real business insights.


This project explores a retail sales dataset using SQL to uncover insights about customers, products, revenue, and sales performance. We used structured queries to break down the business across time, geography, product categories, and customer behavior.

---

## 📁 Dataset Overview

The database consists of 3 main tables:

- `fact_sales`: Contains transactional data like orders, quantity, price, and revenue.
- `dim_customers`: Customer-related information including name, gender, birthdate, and country.
- `dim_products`: Product details including category, cost, and price.

---

## 🔧 Tools Used

- **MySQL** for querying and analysis  
- **Information_Schema** for exploring metadata  
- **Joins, CTEs, Aggregates, and Window Functions** were used across queries

---

## 🎯 Key Business Questions & Insights

### 🧍 Customer Analysis

- We have **18,484 unique customers**, and **all of them have placed at least one order**.
- The **USA leads in customer count**, followed by Australia and the UK.
- Gender distribution is nearly balanced: **~50% Male, ~50% Female**.
- The **oldest customer is around 109 years old**, the youngest around 39.
- Top 10 customers have each contributed **over $12,900 in sales**.
- **3 customers placed only one order**, useful for churn analysis.

### 🌍 Country-Wise Sales

- The **USA leads in total items sold**, followed by Australia and Canada.
- Revenue contribution aligns closely with customer distribution.

### 💰 Sales & Revenue Overview

- **Total revenue: $29.36 million**
- **Total quantity sold: 60,423 units**
- **Average price per unit: $486.04**
- Sales data spans **4 years** (2010–2014)

### 📦 Product Insights

- We have **295 unique products**, spread across 4 main categories: **Bikes, Components, Clothing, Accessories**
- **Bikes are the most valuable category**, generating **96.5% of all sales revenue**
- Top-selling products are all variants of the **Mountain-200 bike**
- Worst-performing products include **low-cost maintenance items** like socks and patch kits
- Cost segmentation shows most products are priced **below $500**

### 📅 Time-Based Analysis

- Monthly trends show how **sales, customer count, and quantity sold** vary across time.
- Helps spot **seasonal patterns and growth trends**.

---

## 📌 Learnings & Takeaways

- CTEs and window functions helped in **percentage contribution and ranking queries**.
- Joining dimension tables brought deeper **customer and product-level understanding**.
- Always inspect for **missing or irregular values** like `'n/a'` in country or gender columns.






