# ☕ Coffee Shop Sales Performance, Revenue Optimization & Consumer Purchase Behavior Analytics

## 📌 Project Overview

This project focuses on performing end-to-end sales analytics on coffee shop transaction data using Python. The primary objective is to analyze sales performance, customer purchasing behavior, product performance, revenue trends, and store-wise sales patterns to support data-driven business decision-making.

The analysis was conducted using Exploratory Data Analysis (EDA), statistical analysis, feature engineering, and data visualization techniques.

---

## 🎯 Project Objectives

- Analyze coffee shop sales performance and revenue trends.
- Understand customer purchasing behavior.
- Identify top-performing products and product categories.
- Evaluate store-wise sales performance.
- Determine peak business hours and customer traffic patterns.
- Generate actionable business insights and recommendations.
- Support inventory optimization and business growth strategies.

---

## 🏢 Domain

**Retail Analytics / Food & Beverage Analytics**

---

## 🛠️ Tools and Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- GitHub

---

## 📊 Dataset Information

| Feature | Description |
|---------|-------------|
| Total Records | 149,116 |
| Total Features | 10 |
| Dataset Type | Transactional Sales Data |
| Domain | Coffee Shop Sales |

### Dataset Columns

- transaction_id
- transaction_date
- transaction_time
- transaction_qty
- store_id
- store_location
- product_id
- unit_price
- product_category
- product_type
- product_detail

---

## 🔧 Data Preprocessing

The following preprocessing steps were performed:

- Missing value analysis
- Duplicate record detection
- Date format conversion
- Feature engineering
- Sales calculation
- Month extraction
- Quarter extraction
- Day name extraction
- Hour extraction
- Sales performance categorization

### Created Features

- Sales
- Month
- Quarter
- Day_Name
- Hour
- Sales_Performance

---

## 📈 Exploratory Data Analysis (EDA)

The following visualizations were created:

### 1. Sales Distribution by Product Category (Box Plot)
- Analyzed variability in product sales.
- Identified high-value transaction categories.

### 2. Sales Distribution by Product Category (Violin Plot)
- Examined customer purchasing patterns.
- Compared transaction density across categories.

### 3. Sales Heatmap by Category and Store
- Compared store-wise revenue contribution.
- Evaluated category performance across locations.

### 4. Unit Price vs Sales (Scatter Plot)
- Studied the relationship between pricing and revenue.

### 5. Correlation Analysis
- Examined relationships among numerical variables.

### 6. Revenue Share by Product Category
- Determined category-wise revenue contribution.

### 7. Sales Distribution Analysis
- Studied customer spending patterns.

### 8. Monthly Revenue Trend
- Analyzed seasonal sales patterns.

### 9. Top 10 Products by Revenue
- Identified highest revenue-generating products.

### 10. Store Performance Analysis
- Compared average sales performance by store.

### 11. Product Category Count
- Analyzed product assortment distribution.

---

## 📌 Key Findings

- Coffee category contributed the highest percentage of total revenue.
- Tea was the second-largest revenue contributor.
- Barista Espresso generated the highest revenue.
- Hell's Kitchen recorded the highest store performance.
- Most customer transactions occurred within low and medium sales ranges.
- Peak business activity occurred during specific hours of the day.
- Transaction quantity showed a strong positive relationship with sales revenue.

---

## 📊 Statistical Analysis

### Skewness Analysis

| Variable | Skewness |
|----------|----------|
| Transaction Quantity | 0.68 |
| Unit Price | 0.09 |
| Sales | 0.90 |

### Observations

- All numerical variables exhibited positive skewness.
- High-value transactions influenced the sales distribution.

---

## 💡 Business Recommendations

- Increase inventory levels for high-performing products.
- Promote top-selling products through marketing campaigns.
- Optimize staffing during peak business hours.
- Implement customer loyalty programs.
- Develop targeted strategies for lower-performing stores.
- Utilize seasonal trends for inventory planning.

---

## 📁 Project Structure

```text
coffee-shop-sales-analytics/
│
├── Coffee_Shop_Sales_Analytics.ipynb
├── Coffee_Shop_Sales.csv
├── Final_Project_Report.pdf
├── dashboard.png
├── README.md
```

---

## 🚀 Project Outcome

This project successfully transformed raw transactional data into actionable business insights using Python-based data analytics techniques. The analysis supports data-driven decision-making for improving revenue, customer satisfaction, inventory management, and operational efficiency.
