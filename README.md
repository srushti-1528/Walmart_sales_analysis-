# 🛒 Walmart Sales Data Analysis

## 📌 Project Overview
This project analyzes **Walmart transactional sales data** to uncover insights about customer behavior, sales trends, and business performance.  
It uses **MySQL** for querying structured data and **Python (Pandas, Matplotlib, Seaborn)** for data analysis and visualization.

---

## 🎯 Objectives
- Identify customer payment preferences.
- Find the busiest sales days and shifts across branches.
- Analyze product category performance (ratings, profit).
- Track revenue changes year-over-year.
- Provide actionable insights for business decision-making.

---

## 🗂️ Dataset
The dataset contains transaction-level information, including:
- **Branch & City**
- **Product Category**
- **Quantity & Unit Price**
- **Profit Margin**
- **Payment Method**
- **Customer Rating**
- **Date & Time of Purchase**
- **Total Sales Amount**

---

## 🔍 SQL Analysis
Key SQL queries included in [`MySQL Queries.sql`]:

1. **Payment Method Analysis**  
   - Count transactions & quantities by payment method.  

2. **Top-Rated Categories**  
   - Identify the highest-rated category in each branch.  

3. **Busiest Day Analysis**  
   - Find the busiest day of the week per branch.  

4. **Shift-Wise Sales**  
   - Categorize sales into Morning, Afternoon, and Evening.  

5. **Category Profitability**  
   - Calculate total profit per category.  

6. **Revenue Trend Analysis**  
   - Compare branch revenues across years and detect declines.  

---

## 📊 Python Analysis
Notebook: [`project.ipynb`]

Steps performed:
- **Data Cleaning & Preprocessing**
  - Date & time conversion
  - Handling missing values  
- **Exploratory Data Analysis (EDA)**
  - Summary statistics  
  - Grouped analysis by branch, city, category, and payment method  
- **Visualizations**
  - Bar charts (payment method, category sales)  
  - Line charts (revenue trend over time)  
  - Heatmaps (correlation analysis)  

---

## 📈 Key Insights
- **Digital Wallets & Credit Cards** are the most used payment methods.  
- **Fridays & Weekends** are the busiest days across branches.  
- **Electronics & Fashion** categories generated the highest profits.  
- A few branches showed **declining revenue year-over-year**, requiring managerial focus.  

---

## 🛠️ Tech Stack
- **Database:** MySQL  
- **Languages:** SQL, Python  
- **Libraries:** Pandas, Matplotlib, Seaborn  
- **Environment:** Jupyter Notebook 
