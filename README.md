📊 Vendor Performance Analysis

End-to-end retail analytics project focused on vendor performance, profitability, purchasing, and inventory efficiency using SQL, Python, and Power BI.

📌 Overview

This project analyzes 116 vendors and ~6,000 brands to identify sales and profitability drivers, vendor dependency, bulk purchasing opportunities, and inventory inefficiencies.

The analysis combines SQL for data preparation, Python for EDA & statistical analysis, and Power BI for interactive reporting.

🎯 Business Objectives

Identify high- and low-performing vendors and brands

Find high-sales but low-margin products

Identify low-sales but high-margin opportunities

Analyze vendor purchase concentration and dependency risk

Measure the impact of bulk purchasing on unit cost

Identify slow-moving inventory and unsold capital

Support purchasing, pricing, and inventory decisions

🔄 Project Workflow

Raw Data → SQL Data Preparation → Aggregated Vendor Dataset
        → Python EDA & Analysis → Power BI Dashboard
        → Business Recommendations

🗂 Dataset

The project uses four business tables:

purchase_prices · purchases · vendor_invoice · sales

The original datasets are too large to host in this repository, so they are available here:

🔗 Kaggle Dataset

The final processed dataset used for the analysis is available in:

data/final_vendor_performance_summary.csv

📁 Repository Structure

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

🔍 Key Analysis

The project covers:

Sales performance of vendors and brands

Profitability and margin analysis

Vendor purchase concentration

Bulk purchasing and unit price analysis

Inventory turnover

Unsold inventory value

Statistical comparison of high- and low-performing vendors

📈 Key Findings

116 vendors and ~6,000 brands analyzed

Top 10 vendors account for ~65.10% of total purchases

91 brands have low sales but high profit margins

21 brands have high sales but low profit margins

Large orders have the lowest average unit purchase price at $11.18

Total unsold inventory capital is approximately $13.21M

Statistical testing shows a significant difference in profit margins between high- and low-performing vendors

📊 Dashboard Preview

Dashboard — Page 1



Dashboard — Page 2



The two-page Power BI dashboard provides an interactive view of sales, vendor contribution, profitability, inventory turnover, unsold capital, and brand performance.

📌 Final Recommendations

Based on the analysis:

Strengthen relationships with major vendors while reducing over-dependence

Negotiate better purchase prices for high-selling, low-margin brands

Promote low-selling, high-margin brands

Reduce purchases of slow-moving products

Use bulk purchasing where inventory demand is predictable

Clear or return excess unsold inventory where possible

Improve inventory turnover through better purchasing and promotions

🛠 Tools & Technologies

SQL · Python (Pandas, Matplotlib, Seaborn, SciPy) · Power BI · Jupyter Notebook

📄 Project Report

For the complete analysis and methodology:

View Detailed Project Report

