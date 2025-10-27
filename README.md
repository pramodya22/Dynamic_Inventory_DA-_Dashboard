# 📊 Excel Dynamic Dashboard

This project showcases a **Dynamic Excel Dashboard** built using Microsoft Excel.
It provides interactive visual insights into inventory data, including total sales, profit, stock levels, and product performance.

---

## 🧠 Project Overview

The dashboard uses Excel formulas, charts, and pivot tables to display **real-time, data-driven KPIs** such as:

* 💰 **Total Sales & Profit**
* 📦 **Stock In / Stock Out**
* 🏬 **Performance by Product & Location**



## 📂 Dataset Information

The dataset includes 1,000 rows of inventory records with the following fields:

| Column           | Description              |
| ---------------- | ------------------------ |
| ID               | Unique record ID         |
| Month            | Month of transaction     |
| Product          | Product name             |
| Balance in Stock | Remaining quantity       |
| Stock In         | Units added to inventory |
| Stock Out        | Units sold               |
| Location         | Sales location           |
| Unit Cost        | Cost per item (LKR)      |
| Total Sales      | Revenue from sales       |
| Profit           | Calculated gross profit  |

Profit was calculated using:

```
Profit = Total Sales - (Stock Out × Unit Cost × 0.8)
```

(Assuming 20% profit margin)

---

## 📈 Features

* Dynamic **Pivot Tables** and **Charts** for analytics
* Slicers for **interactive filtering**
* Visually appealing **KPI cards** and trend charts
* Custom shapes and themes for modern look
* Automatically updates when data changes

---

## 🛠️ Tools Used

* **Microsoft Excel** (for data analysis & visualization)
* **Power Query / Pivot Tables**
* **Conditional Formatting**
* **Formulas** (SUMIFS, AVERAGE, etc.)
* **Custom Shapes and Formatting**

---

## 🚀 How to Use

1. Download the Excel file: `inventory_dashboard_profit.xlsx`
2. Open in Excel (preferably Excel 2019 or later)
3. Explore dashboards using filters or slicers
4. Update or replace data in the “Data” sheet to auto-refresh all visuals

---

## 📸 Screenshot
<img width="967" height="504" alt="Screenshot 2025-10-27 142734" src="https://github.com/user-attachments/assets/45c89b6b-5288-40bc-be4d-b66386a7c2a6" />



---
