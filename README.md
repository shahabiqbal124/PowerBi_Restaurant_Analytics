# PowerBi_Restaurant_Analytics

# 🍽️ Restaurant Sales Dashboard

---

## 📌 Project Overview

This project analyzes restaurant sales data across multiple regions (Birmingham, Liverpool, London, Manchester, etc.) using **Power BI**. The goal was to uncover key business insights such as:

- Year‑over‑year (YoY) revenue trends  
- Units Per Transaction (UPT) stability and spikes  
- Discount impact on revenue  
- Top performing menu items by quantity and revenue  
- Weekday vs. weekend revenue patterns  

The final output is an interactive dashboard that helps stakeholders quickly identify growth opportunities and operational bottlenecks.

---

## 🛠️ Tools Used

- **Power BI Desktop** (May 2026 update)  
- **DAX** for measures and calculated columns  
- **Power Query Editor** for data cleaning  
- **GitHub** for version control  

---

## 💡 Key Insights

1. 📈 **Revenue growth** of **+55.96%** compared to the goal (76.12K actual vs 48.81K goal).  
2. 📊 **UPT remains stable** across most weeks, with occasional spikes in 2025 (e.g., weeks 22–24).  
3. 📅 **Weekends (Sat, Sun)** generate the highest revenue.  
4. 🏷️ **Discounts do not always drive revenue** – some restaurants show high discount % but low revenue.  
5. 🍛 **Top 5 items** drive ~20% of total revenue (Creamy Mushroom Curry leading).  
6. 📉 **YoY decline** observed in certain restaurants (e.g., negative YoY growth bars in the final chart).

---

## 🖼️ Dashboard Snapshot

<img width="1235" height="685" alt="image" src="https://github.com/user-attachments/assets/64f8a484-4d7f-446b-a546-f8a0ee6c6373" />

*The dashboard includes revenue cards, line charts for revenue and UPT by week, scatter plot for discount vs revenue, bar charts for weekday revenue, YoY growth by restaurant, and top menu items by quantity/revenue.*

---

## 🚀 How to Use

1. **Clone or download** this repository to your local machine.  
2. Open **Power BI Desktop**.  
3. Click **File → Open** and select `Restaurant_Sales.pbix`.  
4. If prompted, adjust data source paths to point to the `data/` folder on your machine.  
5. Explore the dashboard pages using the tabs at the bottom.  
6. Use slicers (e.g., date range, restaurant) to filter visuals interactively.

> **Note**: To refresh data, go to **Home → Refresh**. Ensure the CSV files are in the specified location.

---

## 📊 Key Metrics and Visualizations

| Metric / Visual | Description |
|----------------|-------------|
| **Revenue** | Total sales amount after discount |
| **Revenue_PY** | Revenue from the same period in the previous year |
| **Revenue_Change_Amt** | Absolute difference vs previous year |
| **YoY_Growth_%** | Percentage growth compared to previous year |
| **Transaction** | Distinct count of order IDs |
| **UPT (Units Per Transaction)** | Total quantity divided by number of transactions |
| **Total Quantity** | Sum of all items sold |
| **Avg_Transact_Value** | Revenue per transaction |
| **Discount_Pct** | Discount amount divided by gross sales |

**Visualizations included:**
- Line charts: Revenue by week, UPT by week  
- Bar charts: Revenue by weekday, top menu items (quantity & revenue)  
- Scatter plot: Discount % vs Revenue by restaurant  
- Clustered bar chart: Revenue and YoY growth by restaurant  
- Cards: Key KPIs

---

## 💼 Business Impact

- **Identified revenue growth opportunities** by pinpointing weekends and specific menu items (e.g., Creamy Mushroom Curry) as top drivers.  
- **Revealed that high discounts do not guarantee higher revenue** – enabling better discount strategy.  
- **Highlighted consistent YoY decline in certain restaurants** – prompting further operational review.  
- **Stable UPT with occasional spikes** suggests promotional weeks are effective; focus marketing on those periods.  
- **Top 5 items driving 20% of revenue** supports menu optimisation and targeted upselling.
License

This project is for educational/demonstration purposes only.
