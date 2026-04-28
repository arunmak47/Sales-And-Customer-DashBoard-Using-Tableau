# 📊 Sales & Customer Analytics Dashboard — Tableau

An interactive business intelligence dashboard built in **Tableau**, providing a comprehensive view of Sales performance, Customer behavior, and Profitability — with Year-over-Year (YoY) comparisons and dynamic KPI tracking.

---

## 📸 Dashboard Overview

| Dashboard | Description |
|-----------|-------------|
| 🏠 Home | Navigation hub with overview |
| 📈 Sales Dashboard | Sales, Profit, Quantity KPIs with trends |
| 👥 Customer Dashboard | Customer count, Orders, Top 10 Customers |

---

## 🚀 Features

- 📅 **Year-over-Year Comparison** — CY vs PY metrics for Sales, Profit, Orders, Customers, and Quantity
- 📊 **KPI Cards** — Visual indicators showing % change with Above/Below trend markers
- 📉 **Weekly Trends** — Time-series chart highlighting high/low performance periods
- 🏷️ **Subcategory Analysis** — Side-by-side comparison across product subcategories
- 🏆 **Top 10 Customers** — Ranked view of highest-value customers
- 🗺️ **Customer Distribution** — Geographic spread of customers
- 🔄 **Dynamic Filters** — Toggle filters with custom icons; year selection parameter
- 🎨 **Custom UI Design** — Branded layout with logo, icons, and polished navigation

---

## 📐 KPI Metrics Tracked

| KPI | Current Year | Previous Year | % Difference |
|-----|-------------|---------------|--------------|
| Sales | ✅ | ✅ | ✅ |
| Profit | ✅ | ✅ | ✅ |
| Quantity | ✅ | ✅ | ✅ |
| Customers | ✅ | ✅ | ✅ |
| Orders | ✅ | ✅ | ✅ |
| Sales Per Customer | ✅ | ✅ | ✅ |

---

## 🛠️ Tech Stack

| Tool | Purpose |
|------|---------|
| Tableau Desktop | Dashboard creation & visualizations |
| Tableau Hyper (.hyper) | Embedded high-performance data engine |
| Calculated Fields | YoY %, KPI flags, Min/Max logic |
| Parameters | Dynamic year selection |
| Custom Images | Branded icons for navigation and filters |

---

## 📁 Project Structure

```
📦 Tableau.twbx (Packaged Workbook)
 ┣ 📄 PROJECT SALES.twb         # Workbook with all dashboards & sheets
 ┣ 📂 Data/
 ┃   └── federated.hyper        # Embedded data source
 ┗ 📂 Image/
     ┣ Icon - Logo.png
     ┣ Icon - Sales Dashboard.png
     ┣ Icon - Customer Dashboard.png
     ┣ Icon - Filter Shown/Hidden.png
     └── sales image.jpeg
```

---

## 📊 Worksheets Included

- **SALES / PROFIT / QUANTITY** — Trend charts with Min/Max highlights
- **WEEKLY TRENDS** — Weekly breakdown with KPI coloring
- **SUBCATEGORY COMPARISON** — Product-level performance bar chart
- **KPI CUSTOMERS / ORDERS / SALES PER CUSTOMER** — KPI summary cards
- **TOP 10 CUSTOMERS** — Bar chart of highest-value customers
- **CUSTOMER DISTRIBUTION** — Geographic customer map

---

## 🔧 How to Open

1. Install Tableau Desktop or Tableau Public
2. Open `Tableau.twbx` — the `.hyper` data file is embedded, no external connection needed
3. Use the **HOME** dashboard to navigate between Sales and Customer views
4. Use the **Year Parameter** to switch between years for YoY analysis

---

## 💡 Key Calculated Fields

```
CY_SALES            → Current Year total sales (filtered by SELECT_YEAR parameter)
PY_SALES            → Previous Year total sales
% DIFF SALES        → (CY - PY) / PY × 100
Min/Max Sales       → Highlights best and worst performing months
KPI ABOVE BELOW     → ▲/▼ indicator based on YoY comparison
```

---

## 📄 License

MIT License — free to use and adapt for learning or portfolio purposes.
