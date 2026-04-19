# Sirrus.ai Market & Sales Analysis

An end-to-end analytics project built for Sirrus.ai to support market research, internal sales tracking, product bug analysis, and executive reporting.

This project combines SQL, Python, and Power BI to analyze market opportunity, demo performance, developer segmentation, competitor gaps, critical product issues, and monthly leadership decisions.


---

## Project Overview

This repository contains a market and sales analytics project that examines Sirrus.ai's go-to-market performance across six dimensions — demo outcomes, ICP segmentation, city-wise software adoption, market priority scoring, critical bug tracking by module, and executive decision triggers. The output is a Power BI dashboard designed to drive monthly strategic decisions on hiring, engineering resources, and market expansion.

---

## Repository Structure

```
sirrus.ai-market-and-sales-analytics/
│
├── SQL analysis                        # MySQL queries for sales & market data
├── python analysis/                    # Jupyter notebooks — EDA & visualization
├── python analysis output charts/      # Exported chart PNGs from Python
├── Dashboard-images/                   # Power BI dashboard screenshots
└── Sirrus.ai Market & Sales Analysis.pbix   # Full Power BI report
```

---

## Analytics Modules

### 1. Demo Outcomes Analysis
Tracks the result of every sales demo — Rejected, Follow-Up, or Interested — to measure pipeline conversion quality. With 53% of demos resulting in rejection, this module helps identify which cities and segments are underperforming and where sales effort is being wasted.

**Key metrics:** `demo_outcome`, `outcome_count`, `outcome_pct`

---

### 2. ICP Interest Rate by Segment
Measures interest rates across four ICP (Ideal Customer Profile) segments — Enterprise, Small, Large, and Mid. Enterprise leads with the highest interest rate (~26), helping prioritize which segment to target in outbound and marketing campaigns.

**Segments tracked:** `Enterprise` · `Small` · `Large` · `Mid`

---

### 3. Software Adoption — City-Wise
Tracks how many real estate developers in each city have adopted the Sirrus.ai platform. Delhi NCR leads (~30), followed by Mumbai (~28) and Pune (~20). This informs where to double down on sales vs. where to focus acquisition.

**Cities:** `Delhi NCR` · `Mumbai` · `Pune`

---

### 4. Market Priority Score
Ranks cities by a composite market priority score combining adoption potential, ICP density, and deal size. Pune ranks highest (~3K), followed by Mumbai and Bangalore — directly informing where to expand sales headcount.

**Cities ranked:** `Pune` · `Mumbai` · `Bangalore` · `Delhi NCR` · `Hyderabad` · `Indore`

---

### 5. Critical Bugs by Module
Tracks open critical bugs across Sirrus.ai's core modules. Exotel Integration leads with ~30 open bugs, followed by AI Summary Engine and Pre-Sales Module. Used to flag engineering bottlenecks that are directly blocking sales demos and client onboarding.

**Modules tracked:** `Exotel Integration` · `AI Summary Engine` · `Pre-Sales Module` · `Marketing Module`

---

### 6. Decisions Needed This Month (Executive Layer)
A dedicated section on the dashboard surfaces the top 3 strategic decisions required from leadership each month based on the data. This transforms the dashboard from a reporting tool into an active decision-support system.

**Current triggers:**
- Post-sales module delayed 6 weeks → Approve additional engineering resources?
- Telephone Partner integration has 15 critical bugs open → Escalate before first client demo?
- Mumbai has the highest demo interest rate → Hire one additional Mumbai sales rep this month?

---

## Tech Stack

| Tool | Purpose |
|---|---|
| **MySQL** | Raw data queries across sales, demo, adoption, and bug tables |
| **Python (Pandas, Matplotlib, Seaborn, Plotly)** | EDA, metric calculation, chart generation |
| **Power BI** | Executive market & sales dashboard |
| **Excel** | Data validation and supplementary analysis |

---

## Key Insights

- **53% of demos result in rejection** — the pipeline needs qualification improvements before demos are conducted, particularly in lower-priority cities.
- **Enterprise segment** shows the highest ICP interest rate, making it the primary target for outbound sales and product positioning.
- **Delhi NCR leads software adoption** with ~30 clients, but **Pune ranks #1 in market priority score** — suggesting untapped growth potential in Pune.
- **Exotel Integration has the most critical open bugs (~30)** — a direct risk to call quality, AI summary success, and client demos.
- **Mumbai has the highest demo interest rate** among cities not yet fully penetrated, making it the top candidate for additional sales headcount.
- The **Post-Sales module delay of 6 weeks** is creating a retention gap — clients have no structured post-sales engagement tooling during this period.

---

## Power BI Dashboard

The `.pbix` file contains a single-page executive dashboard with full filter support by city and date range.

---

### 📊 Market & Sales Analysis

> Demo Outcomes · ICP Interest Rate by Segment · Software Adoption City-wise · Market Priority Score · Critical Bugs by Module · Decisions Needed This Month

![Sirrus.ai Market & Sales Analysis Dashboard](Sirrus.ai%20Market%20and%20Sales%20Analysis.png)

---

## How to Use

1. Clone the repository
2. Run the SQL queries in `SQL analysis` against your `sirrus_tcg` MySQL database
3. Open the notebooks in `/python analysis` — update data paths as needed
4. Open `Sirrus.ai Market & Sales Analysis.pbix` in Power BI Desktop to explore the dashboard

---

## Author

**Abhishek** — Data Analytics, TCG (The Connect Group)
Working on Sirrus.ai · PropTech SaaS · Real Estate CRM Analytics

---

*Built for market expansion planning and CEO-level monthly decision reviews.*
