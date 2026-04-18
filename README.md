# Sirrus.ai Market & Sales Analysis

An end-to-end analytics project built for Sirrus.ai to support market research, internal sales tracking, product bug analysis, and executive reporting.

This project combines MySQL, SQL, Python, and Power BI to analyze market opportunity, demo performance, developer segmentation, competitor gaps, critical product issues, and monthly leadership decisions.

---

## Project Overview

In the early growth stage of Sirrus.ai, there was no live client analytics available yet, so the focus was on:

- Identifying the most promising real-estate markets
- Analyzing sales demo outcomes and rejection reasons
- Tracking product bugs by module and priority
- Comparing Sirrus.ai features against competitors
- Defining ideal customer segments
- Presenting all findings in a CEO-ready dashboard

The final output is a Power BI executive dashboard supported by SQL queries, Python notebooks, and exported visualizations.

---

## Tools & Technologies

- MySQL
- SQL
- Python
- Pandas
- Matplotlib
- Seaborn
- Power BI
- Jupyter Notebook

---

## Repository Structure

```text
sirrus.ai-market-and-sales-analytics/
│
├── SQL analysis.sql
|
├── Analysis in python/
│   ├── Setup_Data.ipynb
│   ├── Market_Sizing_Analysis.ipynb
│   ├── Competitor_Feature_Matrix.ipynb
│   ├── Demo_Pipeline_Tracker.ipynb
│   ├── Rejection_Reason_Analysis.ipynb
│   ├── ICP_Segmentation.ipynb
│   ├── Bug_Module_Analysis.ipynb
│   ├── Data_Schema_Design.ipynb
│   └── Monthly_CEO_Report.ipynb
│
├── Python analysis charts/
└── Sirrus.ai_Market_and_Sales_Analytics.pbix
```

---

## Key Business Questions Answered

### 1. Market Sizing Analysis
- Which city should Sirrus.ai target first?
- Which markets have the highest opportunity based on developer count, project activity, and software adoption?

### 2. Competitor Feature Matrix
- Which important features are missing in Sirrus.ai compared to competitors?
- Where does Sirrus.ai already have a product advantage?

### 3. Demo Pipeline Tracker
- How many demos converted into interest, rejection, or follow-up?
- Which cities and sales patterns are performing better?

### 4. Rejection Reason Analysis
- Why are prospects rejecting the product?
- Are rejections caused more by pricing, missing features, or integration issues?

### 5. ICP Segmentation
- Which developer segment shows the highest interest?
- Should the company focus on Small, Mid, Large, or Enterprise builders?

### 6. Bug Module Analysis
- Which modules have the most critical bugs?
- Which product areas need immediate engineering attention?

### 7. Monthly CEO Dashboard
A one-page executive summary combining:
- Demo outcomes
- City-wise software adoption
- Critical bugs by module
- ICP interest rate by segment
- Market priority score
- Leadership decisions for the month

---

## Dashboard Preview

![Sirrus.ai Market & Sales Analysis Dashboard](Sirrus.ai%20Market%20and%20Sales%20Analysis.png)

---

## Dashboard KPIs & Insights

### Demo Outcomes
- 53% of demos ended in rejection
- 23% converted into follow-up
- 23% converted into interested prospects

### Software Adoption Citywise
- Delhi NCR shows the highest adoption
- Mumbai is the second strongest market
- Pune has comparatively lower adoption

### Critical Bugs by Module
- Exotel Integration has the highest number of critical bugs
- AI Summary Engine and Pre-Sales Module also require urgent attention

### ICP Interest Rate by Segment
- Enterprise developers show the highest interest
- Mid-sized developers have the lowest conversion

### Market Priority Score
- Pune and Mumbai appear to be the highest-priority cities
- Hyderabad and Indore have comparatively lower market potential

### Leadership Decisions Needed
1. Post-sales module delayed by 6 weeks  
   → Approve additional engineering resources

2. Telephone Partner integration has 15 critical bugs open  
   → Escalate to Telephone Partner before first client demo

3. Mumbai has the highest demo interest rate  
   → Hire one additional Mumbai sales representative

---

## Files Included

- Python notebooks for task-wise analysis
- SQL file containing all analytical queries
- Output chart images generated through Python
- Power BI dashboard file (.pbix)

---

## Business Impact

This project demonstrates how a data analyst can support a growing SaaS product by converting raw business data into decisions around:

- Market expansion
- Sales focus
- Product roadmap priorities
- Bug escalation
- Executive reporting

---

## How to Run

1. Create the MySQL database using the SQL file
2. Run the notebooks in the `Analysis in python` folder
3. Export the generated chart images if needed
4. Open the `.pbix` file in Power BI Desktop
5. Refresh the data and interact with the dashboard

---

## Author

**Abhishek Nalkande**  
Aspiring Data Analyst | Python | SQL | Excel | Power BI

LinkedIn: www.linkedin.com/in/abhishek-nalkande-93216387

---
