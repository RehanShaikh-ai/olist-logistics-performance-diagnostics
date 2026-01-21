# Olist Logistics Performance Diagnostics

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![SQL Server](https://img.shields.io/badge/Data-SQL%20Server-blue)
![Status](https://img.shields.io/badge/Project-Completed-brightgreen)
![Focus](https://img.shields.io/badge/BI-Decision--Driven-orange)
![Visuals](https://img.shields.io/badge/Design-Low%20Clutter-informational)

---

## Overview

This project is a **delivery and logistics performance diagnostic dashboard** built for the **Olist e-commerce platform**, developed using **Power BI** with **SQL Server** as the data source.

The dashboard intentionally avoids visual overload.  
Instead, it follows a **decision-first BI approach**, where each page answers a clearly defined business question.

## Data Source

Public Olist e-commerce order and delivery data, ingested as flat files and loaded into SQL Server for analysis.


Due to file size constraints, the Power BI `.pbix` file is hosted externally.

🔗 **PBIX File (View Only):**  
[[Google Drive Link Here]](https://drive.google.com/file/d/18tEIt1_jQ85rp2z0TK6P4EUNFzSwzzUJ/view?usp=sharing)

---

## Dashboard Pages

### 1) Executive Overview  
**Business Question:** *What is the overall health of deliveries?*

Key metrics at a glance:
- % Delivered Orders
- Average Delivery Time
- % Cancelled Orders

![Executive Overview](/assets/01_health_check.png)

---

### 2) Delivery Performance  
**Business Question:** *Are orders delivered on time, and where does delay come from?*

Highlights:
- On-time delivery rate
- Seller delay vs logistics delay comparison
- Distribution of delivery durations

![Delivery Performance](/assets/02_performance.png)

---

### 3) Logistics Delay Concentration  
**Business Question:** *Which states contribute most to logistics delays?*

Analysis includes:
- Total logistics delay contribution by state
- Delivered order volume comparison
- Scale vs efficiency trade-offs

![Logistics Delay Concentration](/assets/03_impact.png)

---

### 4) Logistics Delay Drivers (Priority States)  
**Business Question:** *Why do São Paulo and Rio de Janeiro behave differently?*

Insights:
- Delay distribution across delivery time ranges
- Structural differences in per-order logistics delay
- Scale-driven vs efficiency-driven delay patterns

![Logistics Delay Drivers](/assets/04_major_drivers.png)

---

## Key Insights

- High on-time delivery rates can **coexist with slow overall delivery experiences**
- **Logistics delays** contribute significantly more than seller delays
- **São Paulo** drives the largest total delay due to high order volume
- **Rio de Janeiro** shows structurally slower per-order logistics performance
- Aggregated KPIs mask regional inefficiencies if not decomposed

---

## Design Philosophy

- Minimal visuals, maximum interpretability  
- One page = one business question  
- Metrics over decoration  
- Analytical clarity over visual density  

> Good BI is not about how many visuals you use, but how clearly your analysis supports decisions.

---

## Tools & Stack

- **Power BI**
  - Data modeling
  - DAX measures
  - Interactive analysis
- **SQL Server**
  - Data extraction
  - Pre-aggregation
- **Olist Public Dataset**

---

## Repository Contents
├── assets <br>
│   ├── 01_health_check.png <br>
│   ├── 02_performance.png  <br>
│   ├── 03_impact.png  <br>
│   └── 04_major_drivers.png  <br>


---

## Final Note

This project prioritizes **decision support**, not dashboard decoration.  
Every visual exists to explain *why* performance looks the way it does and *where* intervention matters.

If a chart doesn’t change a decision, it doesn’t belong here.

---

## **👤 Author**

**Rehan Abdul Gani Shaikh** <br>
**Data Science & ML Student | Python • Power BI | Building Real-World Data Projects**

🔗 Connect with me:  [LinkedIn](https://www.linkedin.com/in/rehan-shaikh-68153a246)  

📬 Email: rehansk.3107@gmail.com

