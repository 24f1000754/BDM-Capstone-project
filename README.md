# BDM Capstone Project — Sales & Inventory Analysis

## 📌 Project Overview

This project was completed as part of the **Business Data Management (BDM) Capstone Project** under the **IIT Madras Online BS Degree Program**.

The project focuses on analysing sales performance, product demand, and inventory management for **Matching Point**, a retail garments business in Muzaffarpur, Bihar.

The main objective was to use real business data to identify inventory-related problems and provide data-driven recommendations for better stock planning and purchasing decisions.

---

## 🏪 Business Profile

**Business Name:** Matching Point  
**Business Type:** B2C Retail Garments Store  
**Location:** Powerhouse Road, Maripur, Muzaffarpur, Bihar  
**Established:** 2014

The business deals mainly in garments and matching accessories such as sarees, suit pieces, dupattas, blouse materials, and other related products.

---

## 🎯 Problem Statements

The project focused on two major business problems:

### 1. Reducing Locked Working Capital
Slow-moving inventory can remain in the store for a long period and lock the business's working capital.

### 2. Minimising Total Inventory Cost
Demand-blind purchasing can lead to overstocking of low-demand products and stockouts of high-demand products.

---

## 📊 Data Used

The project used **primary business data** collected for the period:

**January 2026 – April 2026**

- **699 valid sales transactions**
- **56 SKU/product records**
- Sales register and bill-book data
- Physical stock verification
- Owner discussions

Key variables included:

- Date
- Product Name
- Category
- Quantity Sold
- Selling Price
- Cost Price
- Opening Stock
- Closing Stock
- Total Sales

---

## 🔍 Methodology

The following analytical methods were used:

### 1. ABC Analysis
Used to classify products according to their contribution to total revenue.

### 2. Inventory Turnover Analysis
Used to understand how quickly different products/categories were moving through inventory.

### 3. Descriptive Statistics
Used to understand the basic characteristics and variation in sales and inventory data.

### 4. 7-Day Moving Average Forecasting
Used to smooth daily sales fluctuations and estimate recent demand trends.

### 5. Forecast Accuracy
The moving average forecast was evaluated using:

- MAE
- RMSE
- MAPE

---

## 📈 Key Findings

- **24 unique products** with sales were included in the revenue-based ABC analysis.
- **Class A contained 3 products:** Suit Piece, Saree and Dupatta.
- These three products contributed **67.56% of analysed revenue**.
- Analysed revenue was approximately **₹9,07,565**.
- Closing inventory was **485 units**.
- Estimated locked capital was approximately **₹1,02,600**.
- **Saree** had the highest category-wise inventory turnover at approximately **1.78**.
- **Night Wear** had the lowest category-wise turnover at approximately **0.61**.
- The 7-day moving average forecast had a **MAPE of approximately 44.21%**, indicating that it was useful for identifying recent demand trends but had limited forecasting precision.

---

## 💡 Recommendations

Based on the analysis, the project recommends:

- Give closer monitoring to Class-A and high-demand products.
- Review slow-moving and overstocked products regularly.
- Use recent demand and inventory levels when planning purchases.
- Monitor products approaching stockout conditions.
- Maintain a structured Excel-based inventory tracker.
- Use **Reorder Point (ROP)** and **Safety Stock** concepts for future replenishment planning.
- Collect actual supplier lead-time data for more accurate ROP calculations.

### ROP Formula

`ROP = Average Daily Demand × Lead Time + Safety Stock`

---

## 🛠️ Tools Used

- Microsoft Excel
- Excel Formulas
- Pivot Tables
- Charts & Visualizations
- Inventory Analysis
- Statistical Analysis

---

## 📂 Project Contents

This repository contains the project-related materials such as:

- Project Report
- Presentation
- Excel Analysis Workbook
- Supporting analysis files

---

## 🎓 Project Outcome

This project provided practical experience in working with real-world business data and converting raw sales and inventory information into meaningful business insights.

It helped develop skills in:

- Data Cleaning
- Data Analysis
- Excel
- Inventory Management
- Business Problem Solving
- Data Visualization
- Business Decision Making

---

## 👩‍💻 Author

**Sumaiya Afroz**  
IIT Madras — Online BS Degree Program  
Business Data Management Capstone Project

**Final Score:** 75%  
**Grade:** B
