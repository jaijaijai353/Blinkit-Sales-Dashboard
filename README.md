# Blinkit-Sales-Dashboard
A comprehensive, interactive Power BI dashboard designed to deliver real-time and historical insights into Blinkit’s hyperlocal delivery operations, sales trends, customer behavior, and logistical performance. This solution empowers stakeholders with data-driven decision-making across operations, marketing, and finance.

---

## 🧭 Project Purpose

The objective of this dashboard is to consolidate Blinkit’s transactional and operational data into an intuitive and actionable visual analytics layer. It streamlines performance monitoring, identifies bottlenecks, and highlights growth opportunities in a dynamic, on-demand delivery environment.

---

## 🧱 Key Features

### 🔍 Executive Summary View
- KPIs: Total Revenue, Active Users, Avg. Delivery Time, Cancellation %
- Dynamic Date Range Filtering
- Geo-level insights with state/zone-level breakdowns

### 📊 Sales & Revenue Analysis
- Sales trends: Daily, Weekly, Monthly, Year-over-Year
- Product category performance
- Contribution of promotions and discounts

### 🚚 Operational Efficiency
- Order fulfillment rate & delivery SLA compliance
- Rider performance metrics
- Peak-hour delivery bottlenecks

### 🧍‍♂️ Customer Intelligence
- RFM (Recency, Frequency, Monetary) segmentation
- Retention vs. churn trends
- Acquisition funnel performance

### 📦 Inventory Insights *(Optional)*
- Stockouts vs. overstocked items
- Most returned SKUs
- Vendor-wise delivery delays

---

## 🧰 Tools & Technologies

| Tool/Tech        | Purpose                                      |
|------------------|----------------------------------------------|
| **Power BI**     | Data visualization & report generation       |
| **DAX**          | Custom KPIs, time intelligence calculations  |
| **Power Query**  | Data transformation and ETL                  |
| **Excel/CSV**    | Source data for initial load                 |
| **GitHub**       | Version control and collaboration            |

---

## 🗂 Repository Structure

blinkit-dashboard/
│
├── BlinkitDashboard.pbix # Main Power BI project file
├── README.md # This documentation file
├── /data/ # Sample or anonymized data sources
│ ├── orders.csv
│ └── customers.csv
├── /assets/ # Supporting visuals and documentation
│ └── screenshots/
│ └── overview.png
└── /docs/ # Supplementary documentation
└── data_model.md # Detailed data model & relationships

yaml
Copy
Edit

---

## 📐 Data Model Overview

**Primary Tables**:
- `Orders`: Transactional data containing order ID, timestamp, status, revenue
- `Customers`: User profile, demographics, segment tags
- `Products`: SKU-level product data with category, pricing
- `Deliveries`: Rider assignment, dispatch-to-delivery time
- `Regions`: Geospatial mapping (pincode to region/state)

**Relationships**: Star schema; `Orders` is central fact table linked to dimensions.

---

## 🎯 Intended Audience

| Role | Value |
|------|-------|
| **CXOs / Leadership** | High-level performance metrics and trends |
| **Operations Team** | Delivery time insights, service SLAs |
| **Marketing Analysts** | Customer behavior, RFM, campaign results |
| **Inventory Managers** | SKU performance, stock availability |
| **Data Teams** | Data modeling, KPI definitions, insights pipeline |
📄 License
This project is released under the MIT License. You are free to use, modify, and distribute this for personal or commercial use, with attribution.

✉️ Contact
Created by Jai Narula
