
# 🛒 Target E-commerce SQL Business Case

**SQL (BigQuery) | E-commerce Analytics | Business Insights**

This project analyzes Brazilian e-commerce data from Target’s dataset to understand **customer behavior, order trends, payment patterns, freight costs, and delivery performance** using SQL.
The focus is on translating raw transactional data into **clear business insights and recommendations**.

---

## 🎯 Business Objective

* Understand how customers place orders and pay over time
* Identify demand patterns and seasonality
* Analyze regional differences in freight cost and delivery performance
* Generate actionable insights for marketing, pricing, and logistics teams

---

## 📂 Dataset Overview

The analysis is based on multiple relational datasets commonly used in real-world e-commerce systems.

### Core Tables

* **customers.csv** → customer location and identifiers
* **orders.csv** → order lifecycle and timestamps
* **order_items.csv** → pricing and freight details
* **payments.csv** → payment types and installment behavior
* **products.csv** → product catalog
* **sellers.csv** → seller information

### Supporting Tables

* **geolocation.csv** → geographic mapping
* **order_reviews.csv / order_reviews.xlsx** → customer feedback and ratings

📌 Time range: **2016–2018**
📌 Coverage: **27 states, 4,000+ cities**

---

## 🗄️ SQL Analysis

All analysis was performed using **SQL**, focusing on business-oriented questions rather than academic exercises.

### Key Areas Covered

* Order growth trends and seasonality (yearly & monthly)
* Time-of-day purchase behavior
* Geographic distribution of customers and orders
* Payment methods and installment usage
* Order value and freight cost analysis
* Actual vs estimated delivery performance

📄 SQL file:

```
SQL/target_case_study.sql
```

---

## 📊 Key Insights

* Orders show a **clear upward trend** with seasonal spikes
* **Afternoon and evening** are peak purchasing periods
* Freight costs and delivery timelines vary **significantly by state**
* Installment payments are **widely used**, indicating preference for flexible pricing
* Some regions consistently deliver **faster than estimated**, while others lag

---

## 💡 Business Recommendations

* Run **time-based marketing campaigns** during afternoon and evening peaks
* Apply **region-specific logistics strategies** to reduce freight cost and delays
* Promote **installment-based payment options** to improve conversion
* Revisit delivery ETA models using historical performance data

---

## 📁 Repository Structure

```
Target- SQL Business Case/
│
├── Data/
│   ├── customers.csv
│   ├── geolocation.csv
│   ├── order_items.csv
│   ├── order_reviews.csv
│   ├── order_reviews.xlsx
│   ├── orders.csv
│   ├── payments.csv
│   ├── products.csv
│   └── sellers.csv
│
├── SQL/
│   └── target_case_study.sql
│
├── Insights/
│   └── business_summary.md
│
└── README.md
```

---

## 🧠 Skills Demonstrated

* SQL joins, aggregations, and time-based analysis
* Trend and seasonality analysis
* Customer and payment behavior profiling
* Logistics and delivery performance analysis
* Translating data into business-focused recommendations

---

## 🏁 Conclusion

This project demonstrates how **SQL-driven analysis** can be used to extract meaningful insights from complex e-commerce datasets and support **data-backed business decisions** across marketing, pricing, and operations.

---

## 🔗 Related Files

* 📄 **SQL Queries:** `SQL/target_case_study.sql`
* 📊 **Business Insights:** `Insights/business_summary.md`

 
