## 📊 Influencer Campaign ROI Dashboard

### 🔧 Project Objective

To track and analyze the performance of influencer marketing campaigns across platforms by visualizing key ROI metrics and identifying high-performing influencers, platforms, and categories.

### 📁 Files Included

* `HealthKart_Dashboard.xlsx` – Raw campaign data (influencer name, platform, revenue, orders, ROI, etc.)
* `README.md` – Project overview, assumptions, and setup guide
### ✅ KPIs Tracked

* Total Revenue
* Total Payout
* Average ROI
* Average ROAS
* Total Orders
* Top Influencer by ROI
* Top Platform by Revenue
* Top Category by Revenue

### 📌 Key Assumptions

1. **ROI Formula:**
   ROI = (Revenue - Payout) / Payout
   ROI can be negative if the influencer underperforms.

2. **ROAS Formula:**
   ROAS = Revenue / Payout
   Interpreted as ₹ earned per ₹ spent on that influencer.

3. **Revenue and Payout** are attributed to individual influencers and not campaigns with shared contributors.

4. **Each row** in the dataset represents a unique influencer campaign across a specific platform.

5. Platform-wise and influencer-wise data are **aggregated manually** or via pivot tables.

### 📐 Dashboard Setup Guide

#### ➤ If using **Google Sheets**:

1. Import the `Influencer_Campaign_Data.xlsx`.
2. Use formulas like `SUM()`, `AVERAGE()`, `INDEX()` + `MATCH()` to generate summary KPIs.
3. Use **Pivot Table** to:

   * Group by Platform and sum Revenue
   * Group by Influencer and average ROI
   * Group by Category for campaign effectiveness
4. Create visualizations: Bar charts for Revenue, ROI, and ROAS.
5. Format top row with KPI cards using merged cells, bold fonts, and background colors.

#### ➤ If using **Power BI**:

1. Load the Excel file into Power BI.
2. Create calculated columns:

   * ROI = (Revenue - Payout) / Payout
   * ROAS = Revenue / Payout
3. Create visuals:

   * KPI cards for Total Revenue, ROI, Top Influencer
   * Bar/Column charts: Platform vs Revenue, Category vs Orders
   * Filters for category, platform, or date (if extended)
4. Pin visuals into a clean dashboard layout.


 🧪 Future Improvements

* Add **time-based filters** (week/month/campaign date).
* Track **engagement metrics** like likes, comments, and shares.
* Integrate **cost-per-click (CPC)** or **cost-per-view (CPV)** metrics.
* Expand dataset to include **multi-influencer campaigns**.

