# Customer Behaviour Analysis

## 📌 Project Overview

This project focuses on end-to-end **Customer Behaviour Analysis** using a real-world dataset. The workflow includes **data extraction**, **ETL processing**, **loading into MySQL**, and finally **visualizing insights using Power BI**. The goal is to build a complete analytics pipeline that can be easily replaced with your own business data.

---

## 🎯 Project Objectives

* Extract raw customer behaviour data
* Perform ETL (Extract, Transform, Load) operations using Python 
* Load the cleaned and transformed data into a MySQL database
* Connect Power BI to MySQL
* Build interactive dashboards based on business requirements
* Provide a fully functional analytics setup

---

## 🗂️ Dataset

The project uses a **Customer Behaviour Dataset** that contains information such as:

["customer_id", "age", "gender", "item_purchased", "category", "purchase_amount", "location", "size", "color", "season", "review_rating", "subscription_status", "shipping_type", "discount_applied", "previous_purchases", "payment_method", "frequency_of_purchases", "age_group", "purchase_frequency_days"]


## 🔄 ETL Workflow

### **1. Data Extraction**

* Source dataset is imported from local files.
* Data is inspected and prepared for transformation.

### **2. Data Transformation**

* Data cleaning
* Handling missing values
* Standardizing column names
* Feature creation (if needed)
* Preparing relational tables for MySQL

### **3. Data Loading (MySQL)**

* Structured tables created in MySQL
* Clean data loaded into database
* Relationship modelling for Power BI connectivity

---

## 🗄️ Database Structure (MySQL)

Includes well‑organized tables such as:

* **Customers**
* **Orders**
* **Products**
* **Payments**
* **Shipping**
* **Discounts**

Each table is optimized for Power BI star‑schema modelling.

---

## 📊 Power BI Integration

### **Steps:**

1. Connect Power BI to the MySQL database
2. Import cleaned and transformed tables
3. Build measures and calculated columns
4. Create dashboards as per business requirements:

 * Number Of Customers,
 * Average Of Purchase Amount , 
  *Average Rating Review , 
 * Subscription Status ,
  *Gender ,
  *Revenue By Category, 
 * Sales By Category , 
 * % Of Customer By Subscription Status , 
  *Revenue By Age Group ,
  *Sales Of Age Group , 
  *Category, 
  *Shipping Type

## 📈 Final Deliverables

* ETL‑ready dataset
* MySQL database with clean, structured tables
* Power BI dashboard with full analytics functionality
* README file for GitHub documentation

For queries or collaboration, feel free to reach out!
