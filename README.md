# 📦 Inventory & Supply Chain Management Analysis – Kannan Gurusamy

## 📌 Project Overview
This project provides a comprehensive analysis of inventory health and supply chain efficiency. By integrating data from procurement and sales, the project identifies bottlenecks, optimizes stock levels, and provides actionable insights through data visualization. The workflow covers the full data cycle: **Extraction (SQL)**, **Transformation (Python)**, and **Visualization (Power BI)**.

---

## 🎯 Problem Statement
Inconsistent inventory tracking often leads to:
* **Capital Loss:** Money tied up in overstocked, slow-moving items.
* **Lost Revenue:** Frequent stockouts of high-demand products.
* **Operational Delays:** Unmonitored supplier lead times causing production halts.

This project solves these issues by automating the calculation of safety stocks, reorder points, and identifying product categories that require the most attention.

---

## 📊 Dataset Information
* **Domain:** Supply Chain & Warehouse Management
* **Data Points:** ~[Insert Number, e.g., 2,000+] Rows
* **Key Columns:** * `Product_ID`, `Category`, `Warehouse_Location`
    * `Unit_Cost`, `Selling_Price`, `Quantity_on_Hand`
    * `Lead_Time`, `Reorder_Point`, `Supplier_Performance_Rating`

---

## 🛠️ Tools & Technologies Used
* **Microsoft Power BI:** Developed an interactive dashboard to monitor KPIs.
* **DAX:** Created custom measures for *Inventory Turnover Ratio* and *Stock-to-Sales Ratio*.

---

## 🖼️ Dashboard Preview
* **Please navigate to the `/Images` folder.*

---

## 🚀 Future Enhancements
* **Demand Forecasting:** Implementing a Time-Series model in Python (ARIMA/Prophet) to predict future stock needs.
* **Live API Integration:** Connecting the dashboard to a real-time warehouse management system.
* **Cost Optimization:** Adding a module to calculate the Economic Order Quantity (EOQ) for all Category A items.

---

## ⭐ Conclusion
This project successfully bridges the gap between raw logistics data and strategic business decisions. By implementing these data-driven insights, a business can expect reduced holding costs and a more resilient supply chain.

---
