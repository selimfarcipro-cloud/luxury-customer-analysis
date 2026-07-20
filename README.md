# Customer Behavior Analysis — Luxury Retail

## Project Overview

This project analyzes customer purchasing behavior for a luxury retail company using transactional sales data.

The objective is to transform raw retail transactions into actionable business insights through:

* Data cleaning and preparation
* Exploratory Data Analysis
* RFM customer segmentation
* Revenue and product performance analysis
* Interactive Power BI dashboard reporting

The final dashboard helps answer key business questions:

* Who are the most valuable customers?
* Which segments require retention strategies?
* Which products drive the most revenue?
* How does sales performance evolve over time?

## Dashboard Preview

The final Power BI dashboard provides an interactive overview of customer behavior, revenue performance, and product analysis.

![Customer Behavior Dashboard](images/dashboard_overview.png)

---

# Customer Segmentation — RFM Analysis

Customers are segmented using the RFM framework:

* **Recency** — how recently a customer purchased
* **Frequency** — how often a customer purchases
* **Monetary** — how much revenue a customer generates

This approach identifies different customer profiles:

* Champions
* Loyal customers
* Potential loyal customers
* At-risk customers
* Low-value customers

![RFM Customer Segmentation](images/customer_segments.png)

---

# Revenue Analysis

The project analyzes revenue trends and product performance to identify:

* Monthly revenue evolution
* Best-performing products
* Customer contribution to sales

![Revenue Analysis](images/champions_segments.png)

---

# Product Performance

The analysis highlights the products generating the highest business impact.

Key outputs:

* Top products by revenue
* Sales contribution analysis
* Product ranking

![Top Products Analysis](images/top_products.png)

---

# Data Analysis Workflow

The project follows a complete analytics workflow:

```
Raw Transaction Data
        |
        v
Data Cleaning
        |
        v
Feature Engineering
        |
        v
RFM Customer Segmentation
        |
        v
Business Analysis
        |
        v
Power BI Dashboard
```

---

# Project Structure

```
customer-behavior-analysis-luxury-retail/

├── README.md

├── data/
│   └── processed/
│       ├── rfm_segments.csv
│       ├── ca_mensuel.csv
│       └── top_produits.csv

├── notebooks/
│   └── customer_analysis.ipynb

├── dashboard/
│   └── customer_behavior_dashboard.pbix

├── images/
│   ├── dashboard_overview.png
│   ├── customer_segments.png
│   ├── revenue_analysis.png
│   └── top_products.png

└── requirements.txt
```

---

# Results

The project delivers:

* Customer segmentation based on purchasing behavior
* Identification of high-value customers
* Revenue trend analysis
* Product performance insights
* Interactive business reporting

These outputs can support marketing decisions, customer retention strategies, and revenue optimization.
