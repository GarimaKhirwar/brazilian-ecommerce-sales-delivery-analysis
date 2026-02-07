# 📦 Brazilian E-Commerce Business Analysis

## 📌 Problem Statement
The goal of this project is to analyze the business and operational performance of a Brazilian e-commerce platform using real transactional data. The analysis focuses on answering key business questions around revenue generation, delivery efficiency, customer loyalty, and payment behavior, with the objective of identifying growth drivers, operational bottlenecks, and retention risks.

This project is designed as a **business-oriented data analyst case study**, not just exploratory analysis.

---

## 📊 Dataset
**Brazilian E-Commerce Public Dataset (Olist)**  

The dataset contains multiple interconnected tables covering:
- Orders  
- Order items  
- Customers  
- Sellers  
- Payments  
- Reviews  
- Product categories  

The data spans several years and includes order timestamps, delivery estimates, customer locations, seller performance, and payment details.

---

## 🛠 Tools Used
- **Python**
- **Pandas & NumPy** – data cleaning, joins, aggregation
- **Seaborn & Matplotlib** – visualization
- **Jupyter Notebook** – analysis workflow

---

## 🔍 Analysis Steps
- Cleaned and merged multiple datasets at appropriate levels (order, customer, seller)
- Engineered business features such as:
  - Order value (AOV)
  - Delivery time & late delivery flags
  - Repeat customer indicators
  - Installment payment flags
- Performed aggregation to calculate key business KPIs
- Analyzed trends and patterns across:
  - Sales & revenue
  - Delivery & logistics
  - Customer behavior & loyalty
  - Payment & transaction behavior
- Visualized insights to support business interpretation

---

## 📈 Key Insights

### Sales & Revenue
- Revenue is highly concentrated in a few categories such as **Health & Beauty, Watches & Gifts, and Bed Bath & Table**
- Sales are geographically concentrated in **São Paulo (SP)**
- **November** shows peak sales, while **September** is the weakest month
- **Computers** category has the highest Average Order Value
- A small group of sellers contributes a disproportionate share of revenue
- Freight costs do not scale proportionally with purchase value, limiting AOV growth

### Delivery & Logistics
- Average delivery time is approximately **12 days**
- Late deliveries significantly reduce customer ratings
- A small number of sellers account for the majority of late deliveries (**50–80% late rate**)
- Delivery performance improved over time, but reliability remains a key risk

### Customer Behavior & Loyalty
- Only **13.1%** of customers are repeat buyers
- Repeat customers spend nearly **2× more** per order than new customers
- High-volume states show lower loyalty compared to smaller states
- Repeat customers are **not tolerant** of delivery delays
- Home and security-related categories show stronger repeat purchase behavior

### Payment & Transactions
- **Credit cards** dominate both usage and revenue
- **Installment payments** significantly increase order value
- Payment method does not meaningfully affect cancellations
- **Boleto and voucher** payments show higher late delivery rates than card-based payments

## 📊 Key Visual Insights

### Revenue by Product Category
![Revenue by Product Category](visuals/01_Categories%20with%20highest%20revenue.png)
Revenue is highly concentrated in a few categories, with Health & Beauty, Watches & Gifts, and Bed Bath & Table acting as the primary revenue drivers.

---

### Monthly Sales Trend
![Monthly Sales Trend](visuals/03_Monthly%20Sales%20Trend.png)
Sales exhibit strong seasonality, with peak performance in November and weaker demand in September, highlighting the importance of seasonal planning.

---

### Customer Ratings: Late vs On-Time Deliveries
![Review Score: Late vs On-Time](visuals/15_Review%20Score-%20Late%20vs%20On-Time%20(Re...).png)
Late deliveries receive significantly lower customer ratings, confirming delivery reliability as a critical factor in customer satisfaction.

---

### Installment Payments vs Order Value
![Installment vs Order Value](visuals/19_Installment%20payment%20vs%20Order%20Valu....png)
Orders paid using installment options show a substantially higher average order value, indicating that installment payments enable higher-value purchases.

