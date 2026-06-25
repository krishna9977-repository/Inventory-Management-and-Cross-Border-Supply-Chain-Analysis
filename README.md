# Inventory-Management-and-Cross-Border-Supply-Chain-Analysis
# Inventory Management & Cross-Border Supply Chain Analysis

## Project Overview
This project analyzes a synthetic cross-border e-commerce supply chain dataset 
(25,000 records, 43 attributes) covering January 2023 to December 2024 across 
5 regions, 15 countries, 5 product categories, and 4 warehouses. The goal was 
to identify inventory inefficiencies, profitability gaps, and logistics 
performance issues across the network, and translate findings into actionable 
business recommendations.

The analysis is delivered as a four-page interactive Power BI dashboard covering 
Executive Summary, Inventory Management, Sales & Profits, and Logistics Overview.

---

## Live Dashboard
Click the link below to view the full interactive dashboard:

[View Power BI Dashboard](https://app.powerbi.com/links/KteSQ85U49?ctid=5cdc5b43-d7be-4caa-8173-729e3b0a62d9&pbi_source=linkShare)

---

## Key Findings
- Profit margin is strong and consistent at 39.56% across both 2023 and 2024
- Beauty generates the highest profit ($0.93bn) despite the lowest inventory 
  turnover (1.91x) — outperforming Electronics ($0.39bn) which turns 
  inventory nearly twice as fast (3.50x)
- Over 77% of shipments arrive late — driven directly by lead time 
- Air shipping costs 3x more than Sea ($451.70 vs $152.88) with virtually 
  identical lead time and on-time delivery rate across all three modes
- WH_4 has the highest stockout rate (2.87%) — 31% higher than WH_3 (2.19%) 
  despite serving the same markets
- Marketing spend is proportionally consistent across all 15 countries 
  (1.62-1.73% of revenue) — no market is currently over or under-invested 
  relative to its size

---

## Project Documents

| Document | Description |
| Problem Statement | Business problem, guiding questions, and deliverable overview |
| Methodology & Assumptions| KPI formulas, assumptions, and data limitations |
| Insights & Recommendations | Key findings and actionable recommendations |

---

## Dataset
- **Source:** Synthetic cross-border e-commerce supply chain dataset
- **Records:** 25,000 rows x 43 columns
- **Period:** January 2023 — December 2024
- **Link:** [View on Kaggle](https://www.kaggle.com/datasets/ziya07/cross-border-e-commerce-supply-chain-dataset)

> Note: The raw dataset is not uploaded to this repository. 
> Please access it directly from the Kaggle link above.

---

## Tools Used
- **Power BI Desktop** — data modeling, DAX calculated columns and measures, 
  KPI calculation, dashboard build
- **Power Query** — data load and structure validation
- **Power BI Service** — publishing and sharing

---

## Key Skills Demonstrated
- DAX measure and calculated column development (CALCULATE, SUMMARIZE, 
  AVERAGEX, VAR/RETURN patterns)
- Industry-standard supply chain KPI calculation and interpretation
- Data granularity analysis and correction (identified and resolved 3 
  data structure issues during analysis)
- Cross-functional supply chain analysis (inventory, profitability, logistics)
