# 🏭 SmartInventory 360 – Real-Time Supply Chain & Inventory Dashboard (Power BI)

A complete **Power BI analytics project** built to simulate real-world inventory and supply chain operations.  
This end-to-end solution visualizes performance metrics across **warehouses, suppliers, and product categories**, using realistic Montreal-based data (2023–2025).  

💡 **Built as a portfolio-grade project** to demonstrate business intelligence, supply chain analytics, and Power BI storytelling skills.

---

## 🚀 Project Goals

- Build a **real-time inventory and supply chain analysis dashboard**
- Model and clean datasets using **Power Query**
- Analyze **stock utilization, lead times, turnover, and supplier performance**
- Design **actionable KPIs** with DAX measures
- Create **interactive visuals** for warehouse managers and decision-makers
- Present insights using **storytelling techniques and executive visuals**

---

## 🧰 Tools & Technologies

| Layer | Tools / Skills |
|-------|----------------|
| Data Cleaning & Modeling | Power Query (ETL), Data Types, Transformations |
| Analytics & KPIs | Power BI Desktop, DAX |
| Visualization | Power BI Dashboard (cards, KPIs, bar, line, gauge, donut charts) |
| Data Source | Custom CSV (SmartInventory360_Final_2023_2025.csv) |
| Languages Used | DAX, M (Power Query) |
| Business Skills | Inventory Optimization, Supplier Analysis, Warehouse Utilization, Operations Efficiency |

---

## 🗂️ Data Sources

📊 **Synthetic + Simulated Data** (1200 records)  
Covering the period **Jan 2023 – Sep 2025**

**Attributes**
- **Regions** → Montreal East, West, North, South  
- **Categories** → Consumer Electronics, Home Appliances, Computer Peripherals, Smart Devices  
- **Suppliers** → ElectraTech Inc., Nova Distribution, PixelSource Ltd., Montelix Supply Co.  
- **Warehouses** → Ville-Marie Hub, Laval Distribution Center, Verdun Storage Facility  

📁 Dataset included:  
`data/SmartInventory360_Final_2023_2025.csv`

---

## 📍 Architecture Overview

**1️⃣ Power Query – Data Transformation**
- Imported the CSV dataset  
- Standardized columns, renamed headers, and set data types  
- Added derived columns: lead time, transportation cost normalization, etc.  

**2️⃣ DAX Calculations – Analytical KPIs**
- Warehouse Utilization (%)  
- Days Sales of Inventory (DSI)  
- Inventory Turnover Ratio  
- Average Lead Time by Category  
- Reorder Points & Safety Stock logic  

**3️⃣ Visualization – Power BI Dashboard**
- Executive KPIs  
- Region & Category filters (slicers)  
- Transportation cost and units sold trends  
- Lead time analysis per product type  
- Backorder and fulfillment performance  
- Inventory levels by warehouse and category  

---

## 📊 Dashboard Highlights

**Key Visuals**
- 📦 Warehouse Utilization (Gauge Chart)  
- 🚚 Transportation Cost by Region & Category  
- 📈 Units Sold by Year (Line Chart)  
- ⏱️ Average Lead Time by Category (Donut Chart)  
- 🔄 Backorder Count by Order Status (Bar Chart)  
- 🏭 Inventory Level by Category & Region (Stacked Bar)  

**KPIs on Canvas**
- Warehouse Utilization → 31.16%  
- Days Sales of Inventory → 14.23 days  
- Inventory Turnover Ratio → 23.57  

---

## 📊 Power BI Dashboard Preview

![SmartInventory360 Dashboard](https://github.com/prathmeshgondkar/SmartInventory-360-Real-Time-Supply-Chain-Inventory-Dashboard-Power-BI-/edit/main/README.md)

---

## ✅ Features & Highlights

- 📊 **Single-source analysis:** all-in-one table (cleaned via Power Query)  
- 🧮 **Custom DAX formulas** for KPI precision  
- 🧭 **Dynamic filters** by Region & Category  
- 🧱 **Simple yet enterprise-style layout**  
- 📈 **Actionable storytelling:** replenishment, supplier, and warehouse insights  
- 🖥️ **Fully interactive Power BI dashboard** for real-world presentation  

---

## 🧠 Key Learnings & Skills Demonstrated

- Power Query transformations and modeling  
- DAX for KPI computation  
- Data visualization best practices  
- Business storytelling with analytics  
- End-to-end Power BI project lifecycle  
- Supply chain metrics interpretation  

---

## 📬 Access & Contact

Interested in the dataset, PBIX file, or walkthrough?  
💌 **Connect with me on [LinkedIn](https://www.linkedin.com/in/prathmeshgondkar/)**

---

## ⭐ Like This Project?

If this helped or inspired you, consider starring ⭐ this repository and following for more portfolio-grade projects.

---

## 🗂️ Repository Structure

```
SmartInventory360/
├── data/
│   └── SmartInventory360_Final_2023_2025.csv
├── docs/
│   └── screenshots/
│       └── dashboard.png
├── pbix/
│   └── SmartInventory360.pbix
└── README.md
```
