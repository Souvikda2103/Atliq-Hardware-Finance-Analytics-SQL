# Finance Analytics for Atliq Hardware (SQL Project)

## 📌 Project Overview

This project focuses on building a **SQL-based Finance Analytics system** for *Atliq Hardware*. The objective was to solve real-world business reporting problems by migrating large, Excel-based datasets into a structured SQL database and generating scalable, reusable analytics.

The project demonstrates how SQL can be used not just for querying data, but for **end-to-end business intelligence**, including reporting, classification logic, and performance analysis.

---

## 🎯 Business Problem

Atliq Hardware was facing difficulties in:

* Managing large volumes of sales data in Excel
* Generating consistent and reusable reports
* Performing advanced analysis like rankings and contribution analysis

To address this, the data was migrated into a SQL database where analytics could be performed efficiently and reliably.

---

## 🚀 What This Project Delivers

### 1️⃣ Croma Product-wise Sales Report (FY 2021)

* Generated monthly product-level sales reports
* Implemented a **User Defined Function (UDF)** to handle fiscal year calculations

### 2️⃣ Monthly Sales Reports for Customers

* Built **Stored Procedures** to generate reusable, parameter-driven reports
* Enabled easy reporting for multiple customers and time periods

### 3️⃣ Market Badge Classification

* Created logic to classify markets as **Gold** or **Silver**
* Based on total sold quantity (> 5 million)
* Implemented using a **Stored Procedure**

### 4️⃣ Finance Analytics Layer

* Created SQL **Views** for:

  * Pre-invoice discount
  * Post-invoice discount
  * Net sales
* Used **windows function** for:

  * Ranking customers and products
  * Percentage contribution analysis

---

## 🛠️ Key SQL Concepts Used

* Joins
* User defined Function (UDF)
* Stored Procedure
* Views
* Windows function

---

## 🗂️ Database Objects Created

* Tables for sales, products, customers, pricing, and discounts
* User Defined Functions for fiscal calculations
* Stored Procedures for reports and business logic
* Views for simplified analytics and reporting

---

## 📊 Tools & Technologies

* **Database:** MySQL
* **Language:** SQL
* **Reporting:** SQL Views & Queries
* **Visualization (Output):** Excel / Presentation

---

## 📈 Key Learnings

* Translating business requirements into SQL logic
* Writing reusable and scalable SQL code
* Designing analytics-ready database structures
* Using windows function for advanced analytics

