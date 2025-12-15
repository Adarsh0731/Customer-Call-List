# 📊 Customer Call List – Data Cleaning & Visualization Project

## 📁 Project Overview

The **Customer Call List** project focuses on cleaning, structuring, and visualizing customer contact data used by sales or support teams. The goal is to transform raw data into an analysis-ready format and extract meaningful business insights through visualization.

---

## 📄 Dataset Description

The dataset contains customer contact and interaction details such as names, phone numbers, addresses, contact preferences, and payment status. It helps organizations identify reachable customers, prioritize paying clients, and optimize outbound calling strategies.

---

## 🧹 Data Cleaning Steps

The following data-cleaning operations were performed using **Python (Pandas & NumPy)**:

* Standardized column names (lowercase, underscores)
* Removed special characters from **Last Name**
* Formatted **phone numbers** into `XXX-XXX-XXXX`
* Split **Address** into multiple columns (`address1`, `address2`, etc.)
* Converted categorical values:

  * `Y → Yes`
  * `N → No`
* Handled missing values using an automated rule:

  * > 12% missing → filled using median/mode
  * ≤12% missing → rows dropped
* Removed duplicate records
* Trimmed extra spaces from text columns

The cleaned dataset is saved as **`Customer_Call_List_Cleaned.csv`**.

---

## 📈 Data Visualization

Expert-level visualizations were created to answer business-driven questions:

* Do Not Contact distribution
* Paying vs Non-Paying customers
* Relationship between Paying Customers and Do Not Contact status
* Top States and Cities by customer count
* Paying customer percentage (pie chart)
* Missing values heatmap (data quality check)

These visualizations help improve customer targeting and sales efficiency.

---

## 🛠 Tools & Technologies

* Python
* Pandas & NumPy (Data Cleaning)
* Matplotlib & Seaborn (Data Visualization)
* Jupyter Notebook / VS Code
  
---

## 🎯 Business Value

This project demonstrates an end-to-end data analytics workflow that enables better decision-making, reduces wasted call efforts, improves customer prioritization, and supports data-driven sales strategies.




Just tell me 👍

