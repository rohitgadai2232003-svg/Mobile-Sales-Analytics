# 📱 Mobile Sales Analytics Pipeline

## 📌 Project Overview
This project performs an end-to-end analysis of mobile sales data using Python. The objective is to extract meaningful insights related to sales performance, customer behavior, and market trends, and to support data-driven business decision-making.

---

## 🎯 Objectives
- Analyze sales performance across different mobile brands and models  
- Identify temporal trends in sales (monthly, daily patterns)  
- Understand customer demographics and purchasing behavior  
- Evaluate payment method preferences  
- Generate actionable business insights and recommendations  

---

## 📂 Dataset Description
The dataset contains transactional sales data with the following features:

- **Transaction_ID** – Unique transaction identifier  
- **Day, Month, Year, Day_Name** – Date-related attributes  
- **Brand** – Mobile brand  
- **Mobile_Model** – Model of the mobile device  
- **Units_Sold** – Quantity sold  
- **Price_Per_Unit** – Price per unit  
- **Customer_Name** – Customer identifier  
- **Customer_Age** – Age of customer  
- **City** – Location of purchase  
- **Payment_Method** – Mode of payment  
- **Customer_Rating** – Rating given by customer  

---

## 🛠️ Tech Stack
- Python  
- Pandas  
- Matplotlib  
- Seaborn  
- Jupyter Notebook  

---

## 🔄 Project Workflow

### 1. Data Loading
- Imported dataset using Pandas  
- Verified structure, column names, and data types  

### 2. Data Cleaning
- Handled missing values  
- Standardized column names  
- Converted data types  
- Created new features:
  - **Date** (combined Day, Month, Year)  
  - **Revenue** (Units_Sold × Price_Per_Unit)  

### 3. Exploratory Data Analysis (EDA)
- Brand-wise revenue analysis  
- Monthly sales trends  
- City-wise performance  
- Payment method distribution  
- Customer rating analysis  
- Age group analysis  
- Product (mobile model) performance  
- Day-wise sales patterns  

### 4. Key Insights
- Certain brands and models significantly outperform others  
- Sales exhibit seasonal trends across months  
- Metro cities contribute the majority of revenue  
- Digital payment methods are widely preferred  
- Specific customer age groups drive higher sales  
- Higher customer ratings often correlate with better sales performance  

### 5. Business Decisions
- Optimize inventory by focusing on high-performing products  
- Align marketing campaigns with peak sales periods  
- Promote digital payment options to enhance customer experience  
- Target high-value customer segments  
- Improve quality of low-rated products  
- Expand focus in high-revenue cities  

---

## 📊 Results
The analysis provides a comprehensive understanding of:
- Sales distribution across brands and regions  
- Customer purchasing behavior  
- Revenue-driving factors  

---

## 🚀 Future Enhancements
- Build interactive dashboards using Power BI or Tableau  
- Implement predictive models for sales forecasting  
- Automate data pipeline for real-time analytics  

---

## 👤 Author
**Piyush Vinde**  
**Hardik Pimple**  
**Aneesh Chavan**  
**Rohit Gadai**  
B.Tech Computer Engineering Students