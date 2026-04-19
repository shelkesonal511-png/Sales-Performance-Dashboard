# 📊 Sales Performance Dashboard – Power BI

## 📌 Description
An interactive Power BI dashboard analyzing sales performance across regions, products, and time. This project highlights key revenue drivers, profitability trends, and customer behavior to support data-driven decision-making.

---

## 📖 Project Overview
This project uses the Superstore dataset to build a comprehensive sales dashboard in Power BI. It helps in understanding business performance by visualizing sales trends, profit distribution, and customer insights.

---

## 🎯 Objectives
- Analyze sales across regions and categories  
- Identify top-performing products  
- Understand customer purchasing behavior  
- Evaluate the impact of discounts on profit  
- Track sales trends over time  

---

## 📂 Dataset
The dataset includes:
- Order ID, Order Date, Ship Date  
- Customer Name, Segment, Region, State  
- Product Category, Sub-Category, Product Name  
- Sales, Quantity, Discount, Profit  

---

## 🛠️ Tools & Technologies
- Power BI  
- Power Query Editor  
- DAX (Data Analysis Expressions)  

---

## 🔄 Data Preparation
- Imported dataset into Power BI  
- Cleaned and transformed data using Power Query  
- Fixed data types (Date, Number, Text)  
- Removed unnecessary columns  
- Created a Date Table for time-based analysis  

---

## 🔗 Data Modeling
- Built relationships between tables  
- Connected Date Table with Order Date  
- Optimized model for better performance  

---

## 🧮 DAX Measures

DAX

Total Sales = SUM(Sales)

Total Profit = SUM(Profit)

Profit Margin = DIVIDE(SUM(Profit), SUM(Sales))

Sales YTD = TOTALYTD(SUM(Sales), 'Date'[Date])

Sales MTD = TOTALMTD(SUM(Sales), 'Date'[Date])

## 📊 Dashboard Pages

### 1️⃣ Executive Summary
- KPIs: Total Sales, Total Profit, Profit Margin
- Sales by Region (Map)
- Sales Trend Over Time
- Profit by Category
- Filters: Year, Segment, Region

### 2️⃣ Product Performance
- Top 10 Products by Sales
- Profit vs Discount Analysis
- Sales by Sub-Category

### 3️⃣ Customer Analysis
- Sales by Customer Name
- Sales by Segment
- Repeat vs New Customers

### 4️⃣ Time Intelligence
- Sales YTD vs Last Year
- Monthly Sales Trends
- Seasonality Analysis

## 📸 Screenshots

<img width="1161" height="658" alt="image" src="https://github.com/user-attachments/assets/ecca49af-19ba-4b9d-98bd-35c9c98953d2" />


<img width="1158" height="658" alt="image" src="https://github.com/user-attachments/assets/c606b6ce-3412-49e9-b70a-a9b6ee737b58" />


<img width="1153" height="656" alt="image" src="https://github.com/user-attachments/assets/9e5b9bd3-8934-4986-95d5-70470c7935a1" />


<img width="1157" height="657" alt="image" src="https://github.com/user-attachments/assets/08dd057c-8716-4ffe-ac69-03d56ee17461" />


## 📌 Key Insights
- High discounts can reduce overall profitability
- A small number of products generate most revenue
- Regional performance varies significantly
- Sales follow seasonal trends

## 📎 Conclusion
This dashboard provides a clear and interactive way to analyze sales data, helping businesses make informed decisions and improve performance.

## 🔮 Future Improvements
- Add sales forecasting
- Improve customer segmentation
- Integrate real-time data

## ⭐ If you found this project useful, consider giving it a star!
