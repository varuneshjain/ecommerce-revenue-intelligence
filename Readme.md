# 🛒 E-Commerce Revenue Intelligence & SLA Optimization Platform

A real-world Data Analytics project built using the Brazilian Olist E-Commerce Dataset to uncover revenue trends, customer behavior, and logistics performance issues. The project combines Python-based analysis with interactive Power BI dashboards to help businesses improve decision-making, customer retention, and delivery performance.

---

# 📌 Project Objective

Modern e-commerce businesses generate massive amounts of transactional data, but turning that data into actionable business insights remains a challenge.

This project focuses on solving three key business problems:

### 1️⃣ Revenue Intelligence
- Which states generate the highest revenue?
- Which product categories drive business growth?
- How concentrated is revenue geographically?

### 2️⃣ SLA (Service Level Agreement) Optimization
- How many orders are delivered late?
- What revenue is exposed to delivery delays?
- What is the average customer delivery time?

### 3️⃣ Customer Intelligence
- Who are the most valuable customers?
- Which customers are at risk of churn?
- How does customer value differ across segments?

---

# 📊 Dataset

**Source:** Olist Brazilian E-Commerce Dataset

The dataset contains approximately 100,000+ orders and multiple relational tables including:

| Table | Description |
|---------|------------|
| Customers | Customer information |
| Orders | Order lifecycle details |
| Order Items | Purchased products |
| Products | Product metadata |
| Sellers | Seller information |
| Payments | Payment transactions |
| Reviews | Customer feedback |
| Geolocation | State and city mapping |

---

# 🛠️ Tech Stack

### Data Analysis
- Python
- Pandas
- NumPy

### Data Visualization
- Matplotlib
- Seaborn

### Business Intelligence
- Power BI

### Development Environment
- Jupyter Notebook
- VS Code
- Git & GitHub

---

# 📂 Project Structure

```text
ecommerce-revenue-intelligence/
│
├── data/
│
├── notebooks/
│   ├── 01_data_understanding.ipynb
│   ├── 02_data_quality_assessment.ipynb
│   ├── 03_sla_analysis.ipynb
│   ├── 04_customer_intelligence.ipynb
│   ├── 05_revenue_intelligence.ipynb
│   └── 06_dashboard_dataset_prep.ipynb
│
├── dashboards/
│   └── ecommerce_revenue_intelligence_dashboard.pbix
│
├── images/
│   ├── executive_dashboard.png
│   └── sla_dashboard.png
│
├── reports/
│
├── sql/
│
├── README.md
└── LICENSE
```

---

# 🔍 Key Analysis Performed

## Revenue Analysis

Analyzed sales performance across states and product categories to identify major revenue drivers.

### Key Findings

- Total Revenue: **13.59 Million**
- Top Revenue State: **São Paulo (SP)**
- Top 5 States contribute approximately **74% of total revenue**
- Health & Beauty is the highest revenue-generating category

---

## SLA Analysis

Evaluated delivery performance to measure logistics efficiency and business risk.

### Key Findings

- Late Delivery Rate: **7.87%**
- Revenue Exposure: **8.77%**
- Revenue at Risk: **1.16 Million**
- Average Delivery Time: **12.09 Days**

---

## Customer Intelligence (RFM Analysis)

Customers were segmented using Recency, Frequency, and Monetary analysis.

### Customer Segments

| Segment | Customers |
|----------|----------:|
| Regular Customer | 87,535 |
| VIP Customer | 3,333 |
| At Risk | 2,490 |

### Insights

- VIP customers generate the highest average revenue.
- Regular customers contribute the majority of overall revenue.
- At-risk customers represent potential revenue loss and require retention strategies.

---

# 📈 Power BI Dashboards

## Executive Dashboard

Provides a high-level business overview through:

- Total Revenue KPI
- Total Orders KPI
- Total Customers KPI
- Late Delivery KPI
- Revenue by State
- Revenue by Product Category
- Executive Insights

---

## SLA Optimization Dashboard

Focuses on logistics and delivery performance:

- Late Delivery %
- Revenue Exposure %
- Average Delivery Days
- SLA Performance Insights

---

# 💡 Business Impact

The insights generated through this project can help businesses:

- Improve delivery performance
- Reduce revenue loss due to delays
- Optimize logistics operations
- Increase customer retention
- Identify high-value customer segments
- Prioritize profitable product categories and regions

---

# 🚀 Future Enhancements

- Predict late deliveries using Machine Learning
- Build customer churn prediction models
- Implement real-time KPI monitoring
- Deploy dashboards on Power BI Service
- Create automated reporting pipelines

---

# 👨‍💻 Author

**Varunesh Jain**

Artificial Intelligence & Data Science

Interested in:
- Data Analytics
- Business Intelligence
- Power BI
- Python
- SQL
- Data-Driven Decision Making

---

## ⭐ If you found this project useful, consider giving it a star.