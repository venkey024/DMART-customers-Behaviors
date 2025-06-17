# 🛒 DMart Customer Behavior Analysis

**Objective:**  
This project focuses on understanding customer behavior and improving retail operations using a dataset of 25,000 transactions from DMart. Through data analysis, cleaning, transformation, and visualization using **Python** and **Power BI**, the goal is to uncover actionable insights that support personalized marketing, inventory optimization, and customer satisfaction.

---

## 📁 Dataset Overview

The dataset contains **2,500 customer records** with the following fields:

- Customer ID  
- Product ID  
- Order ID  
- Customer Age  
- Gender  
- Product Name  
- MRP  
- Discount Price  
- Category  
- State  
- City  
- Subscription  
- Bill Number  
- Time Spent on Website  
- Rating  
- Marketing/Advertisement  
- Ship Mode  
- Order Status  
- Order Date  
- Delivery Date  
- Cancellation Date  
- Payment Method  
- Pin Code  
- Total Order Value  
- Payment Status  
- Number of Clicks  
- Year  
- Month  
- Shipping Charges

---

## 🔧 Step 1: Data Loading

- Imported the dataset (2,500 records) into Python for preprocessing and Power BI for visualization.

---

## 🧹 Step 2: Data Preprocessing

- **Missing Values:**
  - `Cancellation Date`: Contains ~23,216 null values.
  - Instead of removing these rows, filled with `"Not Cancelled"` to retain data integrity (based on client requirements).
  
- **Data Type Conversion:**
  - Converted columns like dates and numerical fields into appropriate data types to facilitate analysis and visualization.

---

## 📊 Step 3: Data Visualization (Power BI)

Created a **4-page Power BI report** covering various aspects of customer behavior:

### 1. Home Page  
- Executive overview of customer patterns, sales trends, and KPIs.

### 2. Segmentation  
- Customer segmentation by age, gender, subscription status, and geography.

### 3. Time-Based Insights  
- Seasonal trends, monthly order volumes, delivery performance over time.

### 4. Pricing Efficiency  
- Analysis of MRP vs Discount Price, revenue leakage, and value segmentation.

### 5. Marketing Research ROI  
- Impact of different marketing channels on engagement, time spent, and conversions.

---

## 🧠 Key Outcomes

- **Personalized Marketing:** Identified customer clusters for targeted campaigns.
- **Inventory Optimization:** Demand forecasting using time-based ordering patterns.
- **Customer Service Improvements:** Understanding reasons for cancellations and delivery delays.
- **Sales Strategy:** Effect of pricing and discounting on customer purchase behavior.

---

## 🛠 Tools Used

- **Python** – For data loading, preprocessing, and transformation  
- **Pandas, NumPy** – Data manipulation  
- **Power BI** – Dashboarding and visualization

---

## 📈 Business Impact

This integrated approach helps DMart:
- Improve customer engagement through data-driven personalization
- Enhance operational efficiency by streamlining the supply chain
- Increase revenue through smarter pricing and marketing strategies

