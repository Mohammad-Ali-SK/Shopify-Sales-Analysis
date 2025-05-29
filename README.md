# 🛍️ Shopify Sales Data Analysis & Dashboard

## 📁 Project Overview

This project analyzes a Shopify sales dataset containing over 7,400 real transaction records. Using Python, SQL, and Power BI, the goal was to extract valuable business insights about customer behavior, regional performance, product trends, and revenue optimization.

---

## 📦 Dataset Summary

- **File Name**: `Cleaned_Shopify_Sales.csv`
- **Records**: 7,431 orders
- **Fields**: Order info, product, pricing, customer, country/city, tax, payment gateway
- **Source**: Internal sales data (Shopify-like format)

---

## 🛠️ Tools Used

- **Python** (Pandas, Seaborn, Matplotlib) – EDA & data cleaning  
- **SQL (PostgreSQL)** – For querying and feature extraction  
- **Power BI** – Dashboard design and business insights  
- **Excel** – For final validation & formatting

---

## 📊 EDA Summary

Performed exploratory data analysis to:
- Remove missing and duplicate values
- Feature engineer: revenue per unit, LTV, high tax flag, time features (hour, weekday, month)
- Detect outliers in quantity, tax, and pricing
- Correlation analysis between numerical fields
- Categorical analysis (Gateway, Country, Product Type)

---

## 📈 Power BI Dashboard Highlights

### ✅ KPI Tiles
- Net Sales, Total Customers, Average Order Value, Lifetime Value, Repeat Rate

### 🌍 Geographic View
- Province and city-level performance using maps & bar charts

### ⏱️ Time-Based Trends
- Daily and hourly sales spikes visualized

### 🧾 Payment Gateway Distribution
- Shopify Payments, PayPal, Amazon Pay breakdown

### 🛒 Product Type Sales
- Top-selling products by revenue and quantity

### 📋 Interactive Table
- Drill-down capability for each transaction

---

## 🧩 Key Findings

- 💰 **Net Sales** exceeded $4.6 million  
- 🧍‍♂️ Over **21% of customers** are repeat buyers  
- 🕑 **Peak sales hours** are between 10 AM – 2 PM  
- 🥾 **Climbing Shoes** lead in both quantity sold and total revenue  
- 🌆 Cities like **Austin, Chicago, and San Francisco** generate the highest revenue  
- 💳 **Shopify Payments** used in over 85% of all transactions

---

## 📌 Insights

- Products with high revenue per unit tend to drive lifetime value (LTV)  
- Repeat customers spend significantly more than one-time buyers  
- Shopify Payments is the dominant payment method, suggesting trust in the native platform  
- Tax and total price are perfectly correlated — tax likely calculated as a fixed percentage

---

## 💬 Suggestions

- 📢 Introduce a **loyalty program** to further improve repeat rate  
- 📍 Allocate marketing budget to top-performing cities (Austin, Chicago)  
- 🕒 Launch time-based offers during **mid-day peak hours**  
- 🛒 Bundle or promote best-selling products like Climbing Shoes  
- 💳 Encourage PayPal usage with small discounts to increase flexibility

---

## ✅ Conclusion

This project showcases a full end-to-end data analytics pipeline:

- Cleaned and transformed raw transactional data  
- Performed detailed EDA to uncover meaningful patterns  
- Built an interactive and dynamic Power BI dashboard  
- Delivered actionable insights and business recommendations

The project demonstrates strong skills in **data analysis**, **dashboard design**, and **storytelling with data**.

---

## 📑 Report & Deliverables

| File                          | Description                            |
|-------------------------------|----------------------------------------|
| `Cleaned_Shopify_Sales.csv`   | Final cleaned dataset                  |
| `EDA Process for Shopify.pdf` | EDA process explanation with visuals   |
| `Shopify Power BI Dashboard.pdf` | Dashboard insights summary        |
| `Shopify SQL Queries.sql`     | 30+ SQL queries with answers           |
| `Shopify PPT.pptx`            | Project summary slides                 |
| `README.md`                   | Project documentation (this file)      |

---

## 🧑‍💼 Author

**Mohammad Ali**  
📧 mohammadalisk050@gmail.com  
🔗 https://www.linkedin.com/in/mohammad-ali-sk-316508240/

---

## 📜 License

This project is for educational and demonstration purposes only.

```
