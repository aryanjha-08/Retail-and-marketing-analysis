# Retail Product Performance & Segmentation Analytics

## Project Overview

This project performs end-to-end retail data analysis to evaluate product performance, identify revenue concentration patterns, and segment products using RFM analysis and K-Means clustering.

The objective was to transform raw retail transaction data into actionable insights and build a KPI-driven dashboard for business decision-making.

---

## Business Objectives

* Identify top-performing and low-performing products
* Measure revenue concentration using the Pareto (80/20 rule)
* Segment products using RFM-based clustering
* Detect inactive products (>180 days)
* Track monthly revenue growth trends
* Build dashboard-ready datasets for reporting

---

##  Tech Stack

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Power BI
* Scikit-learn (K-Means Clustering)
* Jupyter Notebook
* Excel

---

## 📂 Dataset Description

The dataset contains retail transactional data, including:

* Year, Month
* Supplier
* Item Code
* Item Description
* Item Type
* Retail Sales
* Retail Transfers
* Warehouse Sales
* Order Date

100K+ transaction records were processed.

---

##  Data Processing Steps

### Data Cleaning

* Handled missing values
* Standardized column formats
* Converted date columns to datetime
* Created Total_Sales feature

###  Feature Engineering

* Computed RFM metrics:

  * Recency
  * Frequency
  * Monetary value
* Created revenue KPIs
* Generated inactivity risk metric (>180 days)

### Product Segmentation

* Standardized RFM features
* Applied **K-Means clustering**
* Identified 6 distinct product segments
* Labeled clusters based on performance characteristics

### KPI Framework

Developed 20+ KPIs, including:

* Total Revenue
* Monthly Growth %
* Revenue Contribution by Segment
* Pareto 80/20 Analysis
* Supplier Performance
* Product Risk Score

---

## Key Insights

* Top 20% products contributed over 70% of total revenue
* 6 product performance segments identified
* Significant revenue concentration observed
* Inactive products (>180 days) flagged for optimization
* Clear supplier performance variation across segments

---

## Dashboard Features (Power BI)

* Revenue trend analysis (monthly)
* Segment-wise revenue contribution
* Product distribution pie/donut charts
* KPI cards (Revenue, Growth %, Risk Score)
* Category & supplier performance view

---

## 📁 Project Structure

```
Retail-Product-Segmentation/
│
├── data/
│   └── processed/
│       ├── cleaned_retail_sales.csv
│       ├── product_rfm.csv
│       └── monthly_kpis.csv
│
├── notebooks/
│   └── retail_analysis.ipynb
│
├── outputs/
│   ├── reports/
│   └── figures/
│
├── dashboards/
│   └── powerbi_dashboard.pbix
│
└── README.md
```

---

## Business Impact

* Enables data-driven inventory decisions
* Supports supplier evaluation
* Identifies revenue-driving SKUs
* Improves risk monitoring
* Provides scalable KPI reporting framework

---

## How to Run the Project

1. Clone the repository
2. Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

3. Run the Jupyter notebook:

```bash
jupyter notebook
```

4. Open Power BI dashboard file for visualization

---

## Future Improvements

* Add demand forecasting using time-series models
* Implement automated ETL pipeline
* Deploy dashboard to Power BI Service
* Integrate predictive inventory optimization

---

## Author

* Aryan Jha
* Data Analyst
* LinkedIn: linkedin.com/in/aryan-jha-4933a7240
* GitHub: github.com/aryanjha-08

---
