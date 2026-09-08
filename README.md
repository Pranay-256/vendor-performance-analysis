# 📊 Vendor Performance Analysis

> **End-to-end retail analytics project focused on vendor performance, profitability, purchasing, and inventory efficiency using SQL, Python, and Power BI.**

---

## 📌 Project Overview

This project analyzes **116 vendors and ~6,000 brands** to identify sales and profitability drivers, vendor dependency, bulk purchasing opportunities, and inventory inefficiencies.

The analysis combines:

- **SQL** → Data Preparation
- **Python** → EDA & Statistical Analysis
- **Power BI** → Interactive Dashboard & Reporting

---

## 🎯 Business Objectives

- Identify high- and low-performing vendors and brands
- Find high-sales but low-margin brands
- Identify low-sales but high-margin opportunities
- Analyze vendor purchase concentration and dependency risk
- Evaluate the impact of bulk purchasing on unit cost
- Identify slow-moving inventory and unsold capital
- Support better purchasing, pricing, and inventory decisions

---

## 🔄 Project Workflow

```text
Raw Data
   ↓
SQL Data Preparation
   ↓
Aggregated Vendor Dataset
   ↓
Python EDA & Analysis
   ↓
Power BI Dashboard
   ↓
Business Recommendations
```

---

## 🗂️ Dataset

The project uses four business tables:

`purchase_prices` · `purchases` · `vendor_invoice` · `sales`

The original datasets are too large to host in this repository.

🔗 [Dataset on Kaggle](https://www.kaggle.com/datasets/harshmadhavan/vendor-performance-analysis?select=vendor_invoice.csv)

The final processed dataset used for the analysis is available here:

`data/final_vendor_performance_summary.csv`

---

## 📁 Repository Structure

```
vendor-performance-analysis/
│
├── README.md
├── vendor_performance_analysis_report.pdf
│
├── dashboard/
│   └── vendor_performance_analysis.pbix
│
├── data/
│   └── final_vendor_performance_summary.csv
│
├── images/
│   ├── dashboard_image1.png
│   └── dashboard_image2.png
│
└── notebooks/
    ├── 01_data_preprocessing.ipynb
    └── 02_eda_&_analysis.ipynb
```

---

## 🔍 Key Analysis

| Analysis Area | Focus |
|---|---|
| Vendor Performance | Top and bottom vendors by sales |
| Brand Performance | High- and low-performing brands |
| Profitability | Profit margins and gross profit |
| Purchase Concentration | Vendor dependency and supply risk |
| Bulk Purchasing | Impact of order size on unit cost |
| Inventory Turnover | Identification of slow-moving inventory |
| Unsold Inventory | Capital tied up in unsold stock |
| Statistical Analysis | Profitability difference between vendor groups |

---

## 📈 Key Findings

- 116 vendors and ~6,000 brands analyzed
- Top 10 vendors contribute ~65.10% of total purchases
- 91 brands have low sales but high profit margins
- 21 brands have high sales but low profit margins
- Large orders have the lowest average unit purchase price at $11.18
- Total unsold inventory capital is approximately $13.21M
- Statistical testing shows a significant difference in profit margins between high- and low-performing vendors

---

## 📊 Dashboard Preview

![Dashboard — Page 1](images/dashboard_image1.png)
![Dashboard — Page 2](images/dashboard_image2.png)

The two-page Power BI dashboard provides an interactive view of:

- Vendor and brand sales performance
- Purchase contribution
- Profitability
- Inventory turnover
- Unsold inventory
- High- and low-performing brands

---

## 💡 Key Business Recommendations

- Diversify the vendor base to reduce dependency on major suppliers
- Negotiate better purchase prices for high-selling, low-margin brands
- Promote low-selling, high-margin brands to increase sales volume
- Reduce purchases of slow-moving products to limit tied-up capital
- Use bulk purchasing strategically where demand is predictable
- Clear or return excess inventory where possible
- Improve inventory turnover through better purchasing and promotional strategies

---

## 🛠️ Tools & Technologies

| Category | Tools |
|---|---|
| Data Preparation | SQL |
| Data Analysis | Python, Pandas |
| Visualization | Matplotlib, Seaborn |
| Statistical Analysis | SciPy |
| Dashboarding | Power BI |
| Development | Jupyter Notebook |

---

## 📓 Project Files

### Python Notebooks

- **01_data_preprocessing.ipynb** — Data preprocessing and preparation workflow.
- **02_eda_&_analysis.ipynb** — Exploratory data analysis, business analysis, visualizations, and statistical testing.

### Power BI Dashboard

`dashboard/vendor_performance_analysis.pbix` — Contains the final interactive two-page dashboard.

### Final Analytical Dataset

`data/final_vendor_performance_summary.csv` — Aggregated vendor-level dataset used for the final analysis.

---

## 📄 Detailed Project Report

For the complete methodology, analysis, visualizations, findings, and recommendations:

📑 [View Detailed Project Report](#)

---

## 👤 Author

**Pranay Jha**

*Data Analytics | SQL | Python | Power BI*
