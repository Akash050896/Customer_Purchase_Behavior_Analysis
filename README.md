
# 🛍️ Customer Purchase Behavior Analysis

![Python](https://img.shields.io/badge/Python-Data%20Preparation-blue?logo=python)
![MS SQL Server](https://img.shields.io/badge/MS%20SQL%20Server-Data%20Analysis-red?logo=microsoftsqlserver)
![Power BI](https://img.shields.io/badge/Power%20BI-Dashboard-yellow?logo=powerbi)
![Domain](https://img.shields.io/badge/Domain-Retail%20Analytics-green)

---

# 🚀 End-to-End Analytics Project

This project demonstrates a **complete analytics workflow**:

**Python → Data Cleaning**

**MS SQL Server → Business Analysis**

**Power BI → Data Visualization**

**GitHub → Project Documentation**

---

# 📌 Project Overview

The **Customer Purchase Behavior Analysis** project analyzes retail transaction data to understand how **customer demographics, product categories, seasons, promotions, and purchasing habits influence revenue generation**.

The analysis combines:

* **Python** for data cleaning and preparation
* **MS SQL Server** for business analysis
* **Power BI** for interactive visualization

The goal of this project is to transform raw retail transaction data into **actionable business insights** that support **marketing optimization, customer engagement, and revenue growth**.

---

# ⭐ Project Highlights

* Analyzed **7,250 retail transaction records**
* Performed **data cleaning and preprocessing using Python (Pandas)**
* Conducted **SQL-based business analysis**
* Built an **interactive Power BI dashboard**
* Identified trends across **customer demographics, product categories, and seasons**
* Generated **data-driven business recommendations**

---

# 📑 Table of Contents

## 📌 Project Overview
- [Project Overview](#-project-overview)
- [Project Highlights](#-project-highlights)

## 🎯 Business Understanding
- [Business Problem](#-business-problem)
- [Project Objectives](#-project-objectives)

## 🔄 Project Workflow
- [Project Workflow](#-project-workflow)
- [Project Architecture](#-project-architecture)
- [Data Flow](#-data-flow)

## 📊 Data & Dashboard
- [Dataset Information](#-dataset-information)
- [Dashboard Structure](#-dashboard-structure)
- [Dashboard Screenshot](#-dashboard-screenshot)

## 📈 Insights & Impact
- [Key Insights](#-key-insights)
- [Business Impact](#-business-impact)
- [Business Recommendations](#-business-recommendations)

## 🧾 Conclusion
- [Conclusion](#-conclusion)

## 🛠 Technical Details
- [Tools & Technologies](#️-tools--technologies)
- [Dashboard Access](#-dashboard-access)
- [Project Repository Structure](#-project-repository-structure)

## 👤 Author
- [Author](#-author)
---

# 🎯 Business Problem

A retail company wants to gain deeper insights into **customer purchasing behavior** across product categories, seasons, shipping preferences, payment methods, subscription status, and promotional usage. 

The company observed fluctuations in seasonal revenue and differences in purchasing patterns between demographic groups.

Key questions include:

* Which seasons generate the highest revenue?
* Which product categories contribute most to sales?
* How do discounts influence customer purchases?
* Which customer segments generate the most revenue?
* What shipping and payment methods are most preferred?

The company aims to use these insights to **optimize marketing strategies, improve customer targeting, and increase revenue growth**. 

---

# 🎯 Project Objectives

* Analyze **revenue trends across product categories**
* Identify **seasonal purchasing patterns**
* Understand **customer demographic behavior**
* Evaluate the impact of **discounts and promotions**
* Examine **shipping and payment preferences**
* Perform **customer segmentation analysis**
* Build an **interactive analytics dashboard**

---

# 🔄 Project Workflow

### 1️⃣ Data Collection

Retail transaction data containing **customer demographics and purchasing information** was used for analysis.

### 2️⃣ Data Cleaning & Preparation (Python)

Python and Pandas were used to:

* Inspect dataset structure
* Handle missing values
* Standardize column names
* Validate dataset consistency
* Prepare structured data for analysis

Customers were grouped into **age segments (18–29, 30–44, 45–59, 60+)**.

---

### 3️⃣ Data Analysis (MS SQL Server)

SQL queries were used to analyze:

* Revenue by gender
* Product category performance
* Seasonal sales trends
* Shipping and payment preferences
* Customer segmentation

---

### 4️⃣ Dashboard Development (Power BI)

An interactive **Power BI dashboard** was developed to visualize:

* Customer demographics
* Product category performance
* Seasonal revenue trends
* Promotional behavior

---

### 5️⃣ Insight Generation

Key trends were interpreted to generate **business insights and recommendations**.

---

# 🏗️ Project Architecture

This project follows an **end-to-end analytics pipeline** converting raw retail data into actionable insights.

| Stage              | Tool            | Purpose                                  |
| ------------------ | --------------- | ---------------------------------------- |
| Data Collection    | CSV Dataset     | Raw retail transaction data              |
| Data Preparation   | Python (Pandas) | Data cleaning and transformation         |
| Data Analysis      | MS SQL Server   | Business query analysis                  |
| Data Visualization | Power BI        | Interactive dashboards                   |
| Documentation      | GitHub          | Project presentation and version control |

---

# 🔄 Data Flow

```
Retail Transaction Dataset (CSV)
            │
            ▼
Data Cleaning & Preparation
Python (Pandas, Jupyter Notebook)
            │
            ▼
Business Analysis
MS SQL Server Queries
            │
            ▼
Data Visualization
Power BI Dashboard
            │
            ▼
Insights & Business Recommendations
            │
            ▼
Project Documentation
GitHub Repository
```

---

# 📊 Dataset Information

The dataset contains **7,250 retail transaction records and 18 columns** representing customer purchases and attributes. 

### Key Dataset Columns

| Column                | Description                  |
| --------------------- | ---------------------------- |
| Customer ID           | Unique customer identifier   |
| Age                   | Customer age                 |
| Gender                | Customer gender              |
| Item Purchased        | Product purchased            |
| Category              | Product category             |
| Purchase Amount (USD) | Transaction value            |
| Season                | Purchase season              |
| Shipping Type         | Shipping preference          |
| Payment Method        | Payment method used          |
| Discount Applied      | Discount indicator           |
| Promo Code Used       | Promo code usage             |
| Subscription Status   | Customer subscription status |
| Review Rating         | Product rating               |
| Previous Purchases    | Number of prior purchases    |

---

# 📊 Dashboard Structure 

The **Power BI dashboard** provides insights into customer purchasing behavior across **categories, seasons, demographics, and promotional strategies**.


### 🔑 Key KPIs

* **Total Customers**
* **Average Purchase Amount**
* **Average Review Rating**

These KPIs provide an overview of **customer spending behavior and satisfaction**.

---

### 📦 Category Performance

| Visualization                   | Chart Type  | Purpose                                                                    |
| ------------------------------- | ----------- | -------------------------------------------------------------------------- |
| Revenue & Customers by Category | Combo Chart | Compare revenue contribution and customer volume across product categories |

---

### 🌦 Seasonal Performance

| Visualization                 | Chart Type  | Purpose                            |
| ----------------------------- | ----------- | ---------------------------------- |
| Revenue & Customers by Season | Combo Chart | Analyze seasonal purchasing trends |

---

### 👥 Customer Demographics

| Visualization                    | Chart Type  | Purpose                                        |
| -------------------------------- | ----------- | ---------------------------------------------- |
| Revenue & Customers by Age Group | Combo Chart | Understand spending patterns across age groups |

---

### 🚚 Shipping Preferences

| Visualization              | Chart Type | Purpose                             |
| -------------------------- | ---------- | ----------------------------------- |
| Customers by Shipping Type | Bar Chart  | Identify preferred shipping methods |

---

### 💳 Payment Behavior

| Visualization               | Chart Type  | Purpose                                 |
| --------------------------- | ----------- | --------------------------------------- |
| Customers by Payment Method | Donut Chart | Display distribution of payment methods |

---

### 🏷 Promotion Impact

| Visualization                    | Chart Type  | Purpose                                       |
| -------------------------------- | ----------- | --------------------------------------------- |
| Customers by Discount Applied    | Donut Chart | Evaluate discount influence on purchases      |
| Customers by Subscription Status | Donut Chart | Compare subscriber vs non-subscriber behavior |
| Customers by Purchase Frequency  | Donut Chart | Analyze purchase frequency patterns           |

---

# 🖼️ Dashboard Screenshot

### 📊 Customer Purchase Behavior

<p align="center">
<img src="Dashboard Screenshot/Customer_Purchase_Behaviour_Dashboard.jpg" width="900">
</p>




---

# 🔎 Key Insights

* **Winter generates the highest revenue**
* **Clothing is the top-performing product category**
* **Customers aged 30–44 generate the highest revenue**
* Discounts significantly influence purchasing decisions
* Free shipping is the most preferred delivery option
* Majority of customers are **non-subscribers**

---

# 📊 Business Impact

This analysis enables retail businesses to:

* Identify **high-performing product categories**
* Understand **seasonal demand trends**
* Target **high-value customer segments**
* Improve **promotion strategies**
* Optimize **inventory planning**

These insights support **data-driven retail decision making**. 

---

# 💡 Business Recommendations

**Improve Seasonal Inventory Planning:**
Prepare inventory and marketing strategies for high-demand seasons.

**Implement Targeted Promotions:**
Use targeted promotions instead of blanket discounts.

**Expand Loyalty Programs:**
Encourage subscription adoption to increase customer retention.

**Focus on High-Value Segments:**
Target marketing campaigns toward the **30–44 age group**.

**Increase Average Order Value:**
Bundle complementary products to increase purchase value.

---
# 🧾 Conclusion

The Customer Purchase Behavior Analysis project demonstrates how retail transaction data can be transformed into actionable business insights through data cleaning, SQL analysis, and interactive visualization.

The analysis highlights key purchasing patterns across product categories, seasons, and customer demographics. These insights enable businesses to better understand customer behavior, optimize marketing strategies, and improve overall revenue performance.

---
# 🛠️ Tools & Technologies


### 🐍 Data Preparation

* **Python (Pandas)** — Data cleaning and preprocessing
* **Jupyter Notebook** — Data exploration environment

### 🧮 Data Analysis

* **MS SQL Server** — Business query analysis

### 📊 Data Visualization

* **Power BI Desktop** — Interactive dashboard development

### 🗂️ Repository Management

* **GitHub** — Version control and project documentation

---

# 📊 Dashboard Access

The interactive dashboard is available in the Power BI report file:

```
PowerBI / Customer_Purchase_Behavior.pbix
```

Open using **Power BI Desktop**.

---

# 📂 Project Repository Structure

```
Customer_Purchase_Behavior_Analysis
│
├── Dataset
│   └── Customer_Purchase_Behavior.csv
│   └── Customer_Purchase_Behavior_Cleaned.csv
|
├── Notebook
│   └── Customer_Purchase_Behavior_Data_Cleaning.ipynb
│
├── SQL
│   └── Customer_Purchase_Behavior_EDA.sql
│
├── PowerBI
│   └── Customer_Purchase_Behavior.pbix
│
├── Screenshots
│   └── SQL_Query_Results
|   └── Customer_Purchase_Behavior_Dashboard.jpg
|
└── README.md
```

# 👤 Author

**Akash Kindre**

Aspiring Data Analyst with hands-on experience in **Power BI, SQL, Excel & Python** specializing in **data visualization, KPI reporting, and dashboard development**. Skilled in **data cleaning, data modeling, and business performance analysis**, with a strong focus on transforming raw data into actionable insights to support data-driven decision-making.
