# Sales & Revenue Performance Dashboard 📊

An interactive Tableau dashboard analyzing sales revenue, quantity, and customer/product performance across Indian markets from 2017–2020.

## 🔍 Overview

This dashboard provides a consolidated view of business performance, enabling stakeholders to filter by **year** and **month** and instantly see how revenue, sales quantity, top markets, top customers, and top products shift over time.

**Snapshot (2020, Jan–Jun):**
- **Total Revenue:** 142M
- **Sales Quantity:** 3,50,259 units
- **Top Market:** Delhi NCR (78M revenue, 143K units)
- **Top Customer:** Electricalsara Stores (65.6M)
- **Top Product:** Prod065 (3.1M normalized amount)

## ✨ Features

- **Year & Month filters** (2017–2020, Jan–Jun) for dynamic time-based analysis
- **Revenue by Market** — horizontal bar chart ranking markets by normalized revenue
- **Sales Quantity by Market** — bar chart of units sold per market
- **Revenue by Year** — trend line showing monthly revenue movement
- **Top 5 Customers** — ranked bar chart by revenue contribution
- **Top 5 Products** — ranked bar chart by normalized sales amount

## 🛠️ Tools Used

- **Tableau** — dashboard design & visualization
- **Excel / CSV** — source data preparation

## 📁 Repository Structure

```
├── README.md
├── screenshots/
│   └── dashboard-overview.png
├── dashboard.twbx          # Tableau packaged workbook (add your file here)
└── data/
    └── sales_data.csv      # source dataset (add your file here)
```

## 🚀 How to View

1. Download Tableau Public or Tableau Desktop (free to view).
2. Clone this repo:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   ```
3. Open `dashboard.twbx` in Tableau.

## 📈 Key Insights

- Delhi NCR dominates both revenue (78M) and sales quantity (143K units), far ahead of Mumbai and Ahmedabad.
- Revenue peaked in February (27M) and declined steadily through June (15M).
- Electricalsara Stores is the single largest customer, contributing more than the next three customers combined.
- Product performance is fairly distributed across the top 5, with Prod065 and Prod018 leading.

