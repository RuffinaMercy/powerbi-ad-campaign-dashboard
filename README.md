Sure! Here's the updated version of your **Power BI project README** with the **Power BI report link** included under a new section called **🔗 Live Dashboard Link**:

---

# 🧠 Online Advertising Analytics Dashboard – Power BI Project

This project is a Power BI dashboard that visualizes and analyzes **online ad campaign performance** using key digital marketing metrics like **CPC, RPC, ROI, CTR, Profit**, and more.

It is built from a raw dataset containing daily ad impressions and enriched using **calculated fields**, allowing deep insight into marketing effectiveness over time.

---

## 📁 Dataset Overview

The original dataset used is:

📄 **`online_advertising_performance_data.csv`**

It includes the following columns:

* `month`, `day`
* `campaign_number`
* `user_engagement` (High / Medium / Low)
* `banner` (ad format)
* `placement` (e.g., abc, def, mno)
* `displays` (total impressions)
* `cost` (total ad cost)
* `clicks` (user clicks on ads)
* `revenue` (earned revenue)
* `post_click_conversions`
* `post_click_sales_amount`

---

## 🧮 Metrics and Calculated Columns (Power BI)

Below are the **DAX formulas** used to derive key performance indicators (KPIs):

| Metric                       | Formula                            |
| ---------------------------- | ---------------------------------- |
| `DATE`                       | `DATE(2020, [MonthNumber], [day])` |
| `CTR` (Click Through Rate)   | `CTR = clicks / displays`          |
| `CPC` (Cost Per Click)       | `CPC = cost / clicks`              |
| `CPM` (Cost Per Mille)       | `CPM = (cost / displays) * 1000`   |
| `Profit`                     | `Profit = revenue - cost`          |
| `ROI` (Return on Investment) | `ROI = Profit / cost`              |
| `RPC` (Revenue Per Click)    | `RPC = revenue / clicks`           |

These were created in Power BI using calculated columns and measures.

---

## 📈 Dashboard Features

* ✅ **Summary Tiles** for:

  * Total Clicks
  * Total Revenue
  * Total Profit
  * CPC, RPC

* 📅 **Line Chart**: Profit by Month

* 📊 **Bar Charts**:

  * Clicks by Campaign Number
  * CPC vs ROI Scatter Plot

* 🧾 **Table View**:

  * Campaign-level insights by month & user engagement

* 🍕 **Pie Chart**:

  * Click Distribution by Placement

---

## 🔍 Insights Gained

* Campaign 1 generated the highest clicks and profit
* Placements like `ghi` and `mno` performed significantly better
* ROI and RPC metrics revealed budget efficiency
* Profit trend shows a **month-over-month decline**, highlighting optimization need

---

## 🚀 How to Use This Project

1. Clone/download the repository
2. Open `AdCampaignDashboard.pbix` in **Power BI Desktop**
3. Load the dataset: `online_advertising_performance_data.csv`
4. Explore and interact with the visuals


---

## 🔗 Live Dashboard Link

👉 **Explore the interactive Power BI report here**:
[🔗 View Dashboard on Power BI Service](https://app.powerbi.com/links/0EKMOxBbgO?ctid=191dd60d-090a-4459-a071-b03c80f3ac3b&pbi_source=linkShare)

---
