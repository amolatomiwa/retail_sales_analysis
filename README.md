# 🛍️ Retail Sales Analysis Report

This project explores a retail sales dataset using **Pandas** and **Matplotlib** in Python. The goal was to practice data cleaning, aggregation, visualization, and report generation — all key skills in Exploratory Data Analysis (EDA).

> 📌 This project was built as part of my learning journey into **Pandas** and **Matplotlib**, with hands-on practice using real-world reporting tasks.

---

## 📂 Dataset Overview

The dataset used in the project includes 1,000+ records of retail transactions, with the following fields:

- `Date`: Transaction date  
- `City`: City where the purchase occurred  
- `Product Category`: Type of product sold  
- `Quantity`: Number of units sold  
- `Sales Person`: Name of the sales representative  
- `Customer Gender`: Gender of the customer  
- `Price per Unit`: Unit price of the item  
- `Total Amount`: Total transaction amount (Quantity × Price)

Additional fields like `Region`, `Month`, and `Weekday` were created during feature engineering.

---

## 🧠 Key Concepts Practiced

- Data cleaning and type conversion  
- Handling missing and irrelevant fields  
- Grouping and aggregating with `groupby()`  
- Creating pivot tables with `pivot_table()`  
- Visualizing data using `Matplotlib` (bar, line, histogram, boxplot)  
- Exporting structured Excel reports with `pd.ExcelWriter`

---

## 📊 Analysis Highlights

✅ **Total Revenue and Units Sold Overall**  
✅ **Monthly Revenue & Quantity (last 6 months)**  
✅ **Top 3 Salespeople by Revenue**  
✅ **Revenue Breakdown by Region (Sum & %)**  
✅ **Pivot Tables by City and Month**  
✅ **Gender-wise Revenue Insights**  
✅ **Visualizations of Trends and Distributions**

---

## 📈 Visualizations Included

- Bar chart: Total sales by city  
- Line chart: Monthly revenue trend  
- Boxplot: Revenue by customer gender  
- Histogram: Price distribution

---

## 📤 Output

A structured Excel report with the following sheets:
- **Monthly Summary**
- **Top Salespeople**
- **Gender-Wise Averages**
- **Revenue Breakdown**
- **Pivot Tables (City & Month)**

All visualizations were created in Jupyter Notebook using Matplotlib and can be viewed in the notebook.

---

## Requirements

- Python 3.x
- Pandas
- Matplotlib

---



## 🚀 How to Run

```bash
# Clone the repository
git clone https://github.com/yourusername/retail-sales-analysis.git

# Install dependencies
pip install pandas matplotlib jupyter

# Launch Jupyter Notebook
jupyter notebook
```

## Getting Started

To explore the notebook, open `retail_sales_analysis.ipynb`.


