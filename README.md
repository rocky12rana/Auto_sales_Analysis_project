# 🚗 Auto Sales Analysis & Customer Behavior Insights

## 📌 Project Overview
This project focuses on analyzing automobile sales data to uncover insights related to **sales performance, customer behavior, and product trends**.  

The analysis helps in understanding **revenue patterns, customer retention, product demand, and regional performance**, enabling better business decision-making.

---

## 📊 Dataset Information
- Total Records: **2,747 rows**
- Features: **21 columns**
- Each row represents a **transaction-level record**
- Includes:
  - Sales & revenue data
  - Customer details
  - Product information
  - Order dates

---

## 🛠️ Tools & Technologies
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🧹 Data Cleaning
- No duplicate records found  
- No missing values detected  
- Converted `ORDERDATE` to datetime format  
- Renamed columns for better readability  

---

## ⚙️ Feature Engineering
- Extracted:
  - **Year**
  - **Month**
- Created:
  - **Revenue_per_item = SALES / QUANTITYORDERED**

---

## 📈 Exploratory Data Analysis

### 🔹 Time-Based Analysis

#### Yearly Revenue
- Revenue increased from **2018 → 2019**
- Drop in 2020 due to **incomplete data**

#### Monthly Revenue
- **November** is the highest revenue month  
- **June** shows lowest sales  
- Clear **seasonal trends** observed  

#### Monthly Comparison by Year
- 2020 data available only until May  
- Highlights importance of **data completeness**

---

### 👥 Customer Analysis

#### Top Customers
- Top 10 customers contribute **~30% of total revenue**
- Revenue moderately concentrated

#### Customer Retention
- **98.9% repeat customers**
- Indicates strong customer loyalty

#### Order Frequency
- Most customers place **1–5 orders**
- Few customers contribute heavily → **long-tail distribution**

---

### 📦 Product Analysis

#### Top Products
- Certain products generate significantly higher revenue
- Top product clearly dominates

#### Product Insights
- Revenue is **skewed toward high-performing products**
- Opportunity to improve mid/low performers

---

### 🏷️ Product Line Analysis
- **Classic Cars** generate highest revenue  
- Other strong categories:
  - Vintage Cars  
  - Trucks & Buses  

- Revenue unevenly distributed across categories

---

### 🌍 Geographical Analysis
- **USA** is the dominant market  
- Strong presence in:
  - Spain  
  - France  

- Growth opportunities in other regions

---

### 💼 Deal Size Analysis
- **Medium deals** contribute the most revenue  
- Small deals provide volume  
- Large deals contribute less → growth opportunity  

---

## 📊 Key Business Insights

### 📌 Sales Insights
- Strong **seasonality in sales**
- Peak performance in **year-end months**

### 📌 Customer Insights
- Highly **loyal customer base**
- Small group of customers drives major revenue

### 📌 Product Insights
- Few products act as **key revenue drivers**
- Demand concentrated in specific items

### 📌 Revenue Distribution
- Balanced contribution from:
  - Top customers
  - Wider customer base

---

## ⚠️ Risks
- Dependence on:
  - **USA market**
  - Top customers & products  
- Low contribution from large deals  
- Incomplete data affecting insights (2020)

---

## 🚀 Opportunities
- Expand into **new geographic markets**  
- Improve performance of low-selling products  
- Increase **high-value transactions**  
- Convert low-frequency buyers into repeat customers  

---

## 🏁 Conclusion
The analysis highlights a **strong and stable business model** driven by loyal customers and high-performing products.  

While the company benefits from consistent revenue streams, there are clear opportunities to:
- Expand geographically  
- Improve product performance  
- Increase high-value sales  

These insights can help drive **data-driven strategies for long-term growth**.

---

## 📷 Visualizations
(https://github.com/rocky12rana/Auto_sales_Analysis_project/tree/main/Assets)

Example:
![Yearly Revenue](images/yearly_revenue.png)

---

## 📂 Project Structure
