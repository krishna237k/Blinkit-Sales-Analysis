# Blinkit Sales & Delivery Data Analysis

## Project Overview
This project focuses on analyzing Blinkit order and delivery data to extract meaningful business insights. The analysis was performed using Python for Exploratory Data Analysis (EDA) and Power BI for building an interactive dashboard.

The objective of this project is to understand order patterns, delivery performance, payment method usage, and overall business metrics.
## Dataset Information

The dataset contains **5000 order records** with the following fields:

- order_id
- customer_id
- order_date
- promised_delivery_time
- actual_delivery_time
- delivery_status
- order_total
- payment_method
- delivery_partner_id
- store_id

These attributes help analyze delivery efficiency, revenue trends, and customer behavior.

---

## Tools & Technologies Used

Python  
Jupyter Notebook  
Pandas  
NumPy  
Matplotlib  
Seaborn  
Power BI  
GitHub  

---

## Project Workflow

### 1 Data Collection
The dataset contains Blinkit order and delivery information used to analyze operational performance.

### 2 Data Cleaning
Data preprocessing steps included:

- Converting date columns to datetime format
- Checking for missing values
- Verifying data consistency
- Preparing data for analysis

### 3 Exploratory Data Analysis (EDA)

EDA was performed in Jupyter Notebook to understand:

- Order distribution
- Delivery performance
- Payment method usage
- Store level activity
- Revenue patterns

Python libraries like **Pandas, Matplotlib, and Seaborn** were used for visualization.

---

## Key Metrics from Analysis

Total Orders: **5000**

Total Revenue: **11,009,308**

Average Order Value: **2201**

On-Time Delivery Rate: **~69%**

---

## Payment Method Distribution

Orders were distributed across multiple payment methods:

- Card
- Cash
- Wallet
- UPI

This indicates a balanced usage of digital and cash payments.

---

## Delivery Performance Insights

Delivery status was categorized as:

- On Time
- Slightly Delayed
- Significantly Delayed

Majority of orders were delivered **on time**, while a smaller percentage experienced delays.

---
Dashboard features include:

- KPI Cards (Total Orders, Revenue, Avg Order Value)
- Order Trends
- Delivery Performance
- Payment Method Analysis
- Store Level Insights
