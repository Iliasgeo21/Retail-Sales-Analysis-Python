<p align="center"> <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python" /> <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-yellow?logo=pandas" /> <img src="https://img.shields.io/badge/Matplotlib-Visualization-orange?logo=plotly" /> <img src="https://img.shields.io/badge/Seaborn-Statistical%20Plots-blue?logo=coffeescript" /> <img src="https://img.shields.io/badge/EDA-Exploratory%20Data%20Analysis-green" /> <img src="https://img.shields.io/badge/RFM-Customer%20Segmentation-purple" /> </p>

# 📦 Retail Sales Analysis Using Python

End-to-End Data Cleaning • EDA • Customer Insights • RFM Segmentation

## 🧾 Project Overview

This project performs a complete analysis of real e-commerce retail sales data, including:

✅ Data cleaning

✅ Exploratory data analysis (EDA)

✅ Revenue & sales trends

✅ Customer shopping behavior

✅ RFM segmentation

✅ Actionable business recommendations

## 📚 Table of Contents

•	Project Overview

•	Dataset Description

•	Repository Structure

•	Technologies Used

•	Data Cleaning

•	Exploratory Data Analysis

•	RFM Segmentation

•	Visualizations

•	Business Insights

•	How to Run

•	License

•	Author

## 📊 Dataset Description

The dataset contains real online retail transaction data including:

•	InvoiceNo — transaction identifier

•	StockCode — product ID

•	Description — product name

•	Quantity — number of units sold

•	InvoiceDate — timestamp

•	UnitPrice — price per item

•	CustomerID — unique customer identifier

•	Country — purchaser location

📌 Source: UCI Machine Learning Repository

📌 Rows: ~500,000

📌 Period: One year of real sales

## 🗂️ Repository Structure

```

Retail-Sales-Analysis-Python/
│
├── data/
│   └── Online Retail.xlsx
│
├── notebook/
│   └── retail_sales_analysis.ipynb     # Main analysis
│
├── src/
│   └── retail_sales_analysis.py        # Script version
│
├── requirements.txt
├── LICENSE
└── README.md

```

## 🧰 Technologies Used

| Category        | Tools                              |
| --------------- | ---------------------------------- |
| Programming     | Python                             |
| Libraries       | Pandas, NumPy, Matplotlib, Seaborn |
| Notebook        | Jupyter / Google Colab             |
| Version Control | Git & GitHub                       |

## 🧼 Data Cleaning

Steps performed:

✅ Removed canceled orders (Quantity < 0)

✅ Filtered invalid invoices

✅ Handled missing values (especially CustomerID)

✅ Removed duplicates

✅ Converted date columns to datetime

✅ Engineered new features:

    •	TotalRevenue = Quantity * UnitPrice
  
    •	InvoiceMonth
  
    •	InvoiceDay
  
📌 After cleaning → dataset reduced from ~541k rows to the valid transaction subset.

## 🔍 Exploratory Data Analysis

✅ Sales Trends

    •	Monthly revenue trends
   
    •	Daily sales patterns
   
    •	Top-selling products
   
    •	Most profitable customers
    
    •	Country-level revenue comparison
   
✅ Customer Behavior

    •	Purchase frequency
   
    •	Spending distribution
   
    •	Average order value
   
    •	Time between purchases
   
📌 These analyses help understand demand patterns & customer shopping habits.

## 🎯 RFM Segmentation

Customers segmented based on:

    •	Recency: days since last purchase
    
    •	Frequency: number of transactions
    
    •	Monetary: total spending
   
✅ Created RFM table

✅ Scaled using quantile scoring

✅ Combined into RFM Score

✅ Grouped into segments (Champions, Loyal, At Risk, etc.)

## 📈 Visualizations

Typical plots generated:

    •	Monthly Revenue Trend

    •	Sales by Country

    •	Top 10 Products
  
    •	Recency/Frequency/Monetary Distributions

    •	RFM Score Heatmap

    •	3D Customer Segmentation Plot

## 💡 Business Insights

Some of the key findings:

✅ 80/20 Rule — A small set of customers generate a large portion of total revenue.

✅ Seasonality — Clear monthly and weekly sales patterns.

✅ High cancellations — Many negative-quantity records indicate operational inefficiencies.

✅ Customer tiers identified — RFM highlighted clear groups:

    •	Champions (high value)
    
    •	Loyal repeat buyers
    
    •	At-risk customers needing reactivation

✅ Product demand concentration: A few product categories dominate sales volume.

These insights can guide:

    •	Targeted marketing
    
    •	Stock optimization
    
    •	Customer retention strategies
    
    •	Pricing and discount policies

## 🚀 How to Run

✅ Option 1 — Run the Notebook

    1.	Clone the repo

    2.	Open the .ipynb file in Jupyter or Google Colab

    3.	Install dependencies:

        pip install -r requirements.txt

    4.	Run all cells

✅ Option 2 — Run Python Script

    python src/retail_sales_analysis.py

## 📜 License

Distributed under the MIT License.

## 👤 Author

Ilias Georgakopoulos
Data Analyst
Bioinformatics & Mathematics
