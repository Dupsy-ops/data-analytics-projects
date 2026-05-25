# E-Commerce Sales Dashboard

**Analysis of Sales Performance, Customer Insights & Geographical Trends**

A data analytics project developed as a Final Project Defence for the Horizon 5-Month Training programme (February 2026), by **Segun, Modupe, and Juwon**.

---

## Overview

This project analyses an e-commerce transactional dataset to uncover revenue trends, customer behaviour, product performance, regional demand, and payment patterns. The deliverable is an interactive Excel dashboard with filters and drilldowns, supported by a slide deck presenting key findings and recommendations.

---

## Key Metrics

| Metric | Value | YoY Change |
|---|---|---|
| Total Revenue | $105M | +16.12% |
| Units Sold | 6M | +16.12% |
| Active Customers | 9.2K | +0.09% |
| Avg Unit Price | $17.6 | -0.01% |

---

## Business Questions Answered

- How much revenue was generated, and how does it compare to last year?
- Which products and units are driving the most sales volume?
- Which countries and regions are the biggest markets?
- Who are the most valuable customers, and how many are being served?
- How do monthly sales trend — growing or declining?
- How do customers prefer to pay, and which payment method dominates?

---

## Data Workflow

```
Data Collection → Data Cleaning → Data Modelling → Analysis → Visualisation
```

1. **Data Collection** — Raw e-commerce transactional dataset
2. **Data Cleaning** (Power Query) — Removed duplicates, handled missing values, standardised formats
3. **Data Modelling** — Built relationships between sales, products, customers & regions
4. **Analysis** — Calculated KPIs: revenue, quantity, avg unit price, customer count
5. **Visualisation** — Built interactive Excel dashboard with filters & drilldowns

---

## Key Findings

### Revenue Performance
- Total revenue reached **$105M**, up **16.12%** vs the previous year.
- May was the strongest month at **$9.08M**; February was the lowest at **$8.07M**.
- Every month stayed within **$8.07M–$9.08M** — a tight, stable range indicating consistent business health.

### Products & Units
- **ct** (count) led quantity sold at **2.18M units**, followed by cans (1.3M) and bottles (840K).
- Unit price is virtually flat (-0.01%) — revenue growth is volume-driven, not price-driven.

### Top Product Categories (by Revenue)
| Rank | Category | Revenue |
|---|---|---|
| 1 | Beverage – Energy/Protein | $10.74M |
| 2 | Food – Healthy | $10.38M |
| 3 | Kitchen Supplies | $8.43M |
| 4 | Food – Chips | $7.76M |
| 5 | Coffee K-Cups | $7.50M |

### Top Markets (by Revenue)
| Rank | Country | Revenue |
|---|---|---|
| 1 | Bangladesh | $13.34M |
| 2 | India | $13.16M |
| 3 | Lithuania | $11.75M |
| 4 | Poland | $10.98M |
| 5 | Germany | $10.96M |

### Regional Performance (Bangladesh Divisions)
| Division | Revenue |
|---|---|
| Sylhet | $43.4M |
| Barisal | $41.4M |
| Rangpur | $40.5M |
| Rajshahi | $37.6M |
| Chittagong | $36.8M |
| Khulna | $29.2M |
| Dhaka | $8.2M |

> Dhaka — despite being the capital — records the lowest sales at just $8M and requires urgent review.

### Customer Insights
- **9.2K** active customers with only **+0.09%** growth — a major area for improvement.
- Top customer **Pooja** leads at **121K** in purchases, 1.6× ahead of the second-highest (Jyoti at 76K).
- Heavy reliance on a small top-customer group creates concentration risk.

### Payment Methods
| Method | Revenue Share |
|---|---|
| Card | $94.6M (~90%) |
| Mobile | $8.1M |
| Cash | $2.7M |

### Weekly Sales Trend
| Week | Revenue |
|---|---|
| 4th Week | $32.96M |
| 3rd Week | $24.23M |
| 1st Week | $24.13M |
| 2nd Week | $24.09M |

### Suppliers
BIGSO AB, Bolsius Boxmeer, CHERRY GROUP CO. LTD, CHROMADURLIN S.A.S, DENIMACH LTD, Friedola 1888 GmbH, HARDFORD AB, Indo Count Industries Ltd, MAESA SAS, NINGBO SEDUNO IMP & EXP CO. LTD

---

## Recommendations

1. **Scale Bangladesh operations** — top market at $13.34M; invest in local warehousing & logistics.
2. **Grow the customer base** — launch referral programmes, digital ads & retention campaigns.
3. **Capitalise on top products** — prioritise stock depth and bundle deals for Beverage/Energy and Healthy Food lines.
4. **Diversify payment options** — 2% cash signals untapped mobile money opportunity in emerging markets.
5. **Fix Dhaka's underperformance** — review distribution channels, pricing, and local partnerships urgently.
6. **Introduce subscription models** — Coffee K-Cups and repeat-purchase categories are strong candidates for recurring revenue.

---

## Files in This Repository

| File | Description |
|---|---|
| `E-commerce analysis.xlsx` | Excel workbook with raw data, pivot tables, KPIs, and interactive dashboard |
| `E-commerce final slide.pptx` | Presentation slide deck with insights and recommendations |
| `E-commerce wireframe.pptx` | Dashboard wireframe and design planning |
| `Customer Churn Dashboard.xlsx` | Customer churn analysis workbook |
| `Sample Superstore data.pbix` | Power BI report on superstore sales data |
| `Worked on sales data set.xlsx` | Sales dataset workbook |
| `Resturant Dashboard.xlsx` | Restaurant sales dashboard workbook |

---

## Tools Used

- **Microsoft Excel** — Data cleaning, pivot tables, KPI calculations, dashboard
- **Power Query** — Data transformation and cleaning
- **Microsoft PowerPoint** — Presentation and wireframing
- **Power BI** — Additional data visualisation (Superstore dataset)

---

*Horizon 5-Month Data Analytics Training — Final Project Defence, February 2026*
