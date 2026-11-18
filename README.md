# 📦 Samsung Supply Chain & Logistics Dashboard

An interactive **Power BI** dashboard that gives end-to-end visibility into Samsung's supply chain — from suppliers and procurement, through inventory and shipment, to customers and sales channels.

<img width="1331" height="747" alt="Screenshot 1 " src="https://github.com/user-attachments/assets/ccb94eea-bc37-4de1-83ac-2da8c46d7c62" />

---

## 📌 Table of Contents
- [Project Overview](#-project-overview)
- [Business Questions](#-business-questions)
- [Dashboard Pages](#-dashboard-pages)
- [Key Metrics](#-key-metrics)
- [Key Insights](#-key-insights)
- [Tools & Skills](#-tools--skills)
- [Project Structure](#-project-structure)
- [How to Use](#-how-to-use)
- [Author](#-author)

---

## 🎯 Project Overview

Supply chain data is usually scattered across suppliers, warehouses, carriers and sales platforms. This project brings it all into **one navigable report** with 6 pages, so a decision-maker can move from a high-level KPI view down to the details of each stage.

**Goals**
- Monitor revenue, profit and order performance in one place
- Evaluate suppliers by lead time, quality and cost
- Track inventory levels against safety stock and reorder points
- Identify carrier delays and their root causes
- Understand which channels and customers drive revenue

---

## ❓ Business Questions

| Area | Question |
|------|----------|
| Supplier | Which supplier has the best lead time? What does procurement cost look like month by month? |
| Inventory | Which products are over/under stocked vs. safety stock and reorder point? When do defects spike? |
| Shipment | Which carrier has the most delays, and what are the main delay reasons? |
| Customer | Which platform/customer generates the highest revenue and profit? How do discounts vary by category? |

---

## 🖼️ Dashboard Pages

### 1. Home
Landing page with navigation to all sections.

### 2. Overview
High-level KPIs (revenue, profit, margin, perfect order %) plus entry points to each section, with quick charts for supplier lead time, inventory stock, delays by carrier and revenue by platform.

![Overview] <img width="1327" height="740" alt="Screenshot 2" src="https://github.com/user-attachments/assets/73076184-8d04-4309-ab53-82103a121623" />


### 3. Supplier
Procurement and supplier performance: unit cost, order quantity by month, lead time, quality score, revenue/profit split by product category, and a detailed product table.

![Supplier]<img width="1435" height="805" alt="Screenshot 3" src="https://github.com/user-attachments/assets/e7aed304-c98a-497b-9241-7bdcb792fa79" />


### 4. Inventory & Production
Inventory value, safety stock, turnover, defective units, monthly trends, and current stock vs. safety stock vs. reorder point by product.

![Inventory]<img width="1432" height="812" alt="Screenshot4" src="https://github.com/user-attachments/assets/0a7067dc-6b54-4788-b4dc-900441c2b27b" />


### 5. Shipment
Shipment volume and cost, delivered vs. delayed shipments by carrier, shipment status, monthly shipment cost, and delay reasons.

![Shipment]<img width="1426" height="800" alt="Screenshot 5" src="https://github.com/user-attachments/assets/8d93614b-80c1-4caa-9065-70b6316db1f3" />


### 6. Customer
Revenue and profit by channel type and customer, discount analysis by category and product, and growth trend by month.

![Customer]<img width="1428" height="791" alt="Screenshot 6" src="https://github.com/user-attachments/assets/8ec55d3d-c7c7-458c-a4ac-2a4852e6fb0d" />


---

## 📊 Key Metrics

| Metric | Value |
|--------|-------|
| Gross Revenue | 186.86M |
| Total Revenue | 176.95M |
| Total Profit | 48.56M |
| Profit Margin | 27.44% |
| Perfect Order % | 75% |
| Total Shipments | 8K |
| Shipment Cost | 19.42M |
| Delivered % | 75.29% |
| Total Unit Cost (procurement) | 78.13M |
| Order Quantity | 129K |
| Avg Lead Time | 11.53 days |
| Avg Quality Score | 96.63 |
| Number of Suppliers | 7 |
| Defective Units | 24K |
| Total Discount | 9.92M |

---

## 💡 Key Insights

- **Smartphones dominate the business:** ~55.8% of revenue (98.71M) and ~53.4% of profit (25.93M) come from the smartphone category.
- **Q4 pressure on procurement:** order quantity peaks in December (14.5K) and procurement cost hits its highest in October and December (~8.0M each).
- **Supplier lead times are tightly grouped:** five suppliers sit at 12 days, while Samsung's internal units are at 9 days.
- **Carrier delays:** Maersk Line has the most delays (87), followed by DHL Express (66) and DB Schenker (65). Top delay reasons are carrier capacity (90), documentation (78) and port congestion (73).
- **Defects spike in Q4:** average defective units jump from ~4.9 in September to ~7.0 in October, alongside the peak in inventory value.
- **Revenue is evenly spread across platforms:** Amazon (37M), Flipkart (36M), Best Buy (36M) and MediaMarkt (35M) are close, with Samsung's own channel at 32M.

---

## 🛠️ Tools & Skills

- **Power BI Desktop** – report design, navigation, interactive visuals
- **DAX** – measures and KPIs (profit margin, delivered %, perfect order %, etc.)
- **Power Query** – data cleaning and transformation
- **Data Modeling** – star schema across suppliers, products, shipments, inventory and customers
- 📧 Email: _add your email_

⭐ If you found this project useful, feel free to star the repo!
