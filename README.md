# Inventory & Supply Chain Management Analysis Dashboard

## 📌 Project Overview
Efficient supply chain and inventory operations are critical for maintaining business profitability, minimizing holding costs, and avoiding stockouts. This project features a comprehensive **Power BI Dashboard** designed to monitor real-time inventory health, tracking fulfillment statuses, and analyzing logistical costs.

By transforming raw supply chain records into an interactive data narrative, this dashboard allows operational managers to quickly identify regional bottlenecks, optimize warehouse storage capacity, and track sales performance over multi-year periods.

---

## 🛠️ Tech Stack & Skills Demonstrated
* **Business Intelligence:** Power BI Desktop
* **Data Modeling:** Star Schema design involving sales, logistics, and inventory metrics.
* **DAX (Data Analysis Expressions):** Created custom measures for critical supply chain metrics including operational KPIs, averages, and multi-year summations.
* **Power Query (M Language):** ETL processing to clean, transform, and structure categorical variables (Regions, Order Statuses, Product Categories).
* **Data Visualization:** Built an intuitive executive layout utilizing KPI cards, gauge charts, donut charts, trend lines, and custom color themes for maximum scannability.

---

## 📊 Dashboard Architecture & Visual Breakdown

Based on the core dashboard page, the analytical architecture is split into three main operational pillars:

### 1. Key Performance Indicators (KPIs)
* **Warehouse Utilization (34.08%):** A dedicated gauge chart displaying current storage usage against total capacity constraints, signaling available space.
* **Days Sales of Inventory (15.56 Days):** Tracks the average number of days it takes to turn inventory into sales, indicating highly efficient inventory liquidity.
* **Inventory Turnover Ratio (28.15K):** Displays how frequently the business sells and replaces its inventory over the tracking period.

### 2. Logistics & Operational Distribution
* **Transportation Cost by Region & Category:** A clustered column chart breaking down shipping expenses across the North, West, East, and South regions, categorized by product types (Accessories, Clothing, Electronics, Furniture).
* **Average of Lead Time by Category:** A donut chart showing the efficiency of fulfillment cycles across product lines, identifying which categories experience longer procurement delays.
* **Count of Backorder by Order Status:** A clear bar chart highlighting volume across *Fulfilled*, *Pending*, and *Canceled* orders to track pipeline friction.

### 3. Sales Trends & Stock Distribution
* **Units Sold by Year:** A historical trend line tracking sales volume performance across multiple years (2020–2024), capturing the sharp growth spike post-2021.
* **Inventory Level by Category & Region:** A horizontal stacked bar chart showing the exact cross-sectional balance of stock volume globally across multiple territories.

---

## 💡 Interactivity & Filters
To allow deep-dive analysis, the dashboard includes dynamic, cross-filtering capabilities via left-hand slicers:
* **Region Slicer:** Filter the entire canvas to focus on a single territory (e.g., *North* or *West*).
* **Category Slicer:** Drill down into specific product segments to isolate individual logistical challenges.

---

## 📈 Key Formula Frameworks
* **Days Sales of Inventory (DSI):** $\text{DSI} = \left( \frac{\text{Average Inventory}}{\text{Cost of Goods Sold (COGS)}} \right) \times 365$
* **Warehouse Utilization Rate:** $\text{Utilization \%} = \left( \frac{\text{Occupied Storage Volume}}{\text{Total Available Capacity}} \right) \times 100$

---

## 🧑‍💻 How to Run and View the Project
1. **Clone the Repository:**
   ```bash
   git clone [https://github.com/Hariprakash-R-2410/Inventory-Supplychain-Management.git](https://github.com/Hariprakash-R-2410/Inventory-Supplychain-Management.git)
