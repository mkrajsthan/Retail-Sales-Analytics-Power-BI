# Retail Sales Analytics — SQL Server + Power BI

End-to-end retail/FMCG sales analytics project: SQL Server for data
processing and business-question queries, Power BI for a 5-page interactive
dashboard covering revenue, regional, product, and customer performance.

## Business Questions This Answers

- Which categories, regions, and channels drive the most revenue and margin?
- How does discounting affect revenue and profitability?
- Which customer segments are the most valuable and the most retained?
- Which products are top performers vs. flagged for review (high returns)?

## 📈 Dataset

- 10,000-row retail/FMCG sales dataset (India-specific), FY 2026
- Columns: order, product, category, pricing, discount, revenue, margin,
  profit, region, city, channel, customer segment, returns
- *(A sample is included in `/data`; full dataset available on request.)*

## Tools & Approach

| Stage | Tool |
|---|---|
| Data staging & validation | SQL Server (SSMS) |
| Business analysis queries | T-SQL - queries covering KPIs, trends, segmentation |
| Data model & measures | Power BI (DAX) |
| Dashboard | Power BI — 5 pages |

## 📊 Dashboard Pages

| Page | Focus |
|---|---|
| Overview | Top-line KPIs and trends |
| Regional | Performance by region and Share |
| Products | Category/product revenue, margin, returns, performance grading |
| Customers | Segment revenue, retention, repeat purchase behavior |
| Summary | Summarized view |

<img width="1275" height="712" alt="image" src="https://github.com/user-attachments/assets/3fb9bf12-0e4f-456d-9926-1a90086b93ff" />
<img width="1515" height="848" alt="image" src="https://github.com/user-attachments/assets/9a7301d5-e36f-4436-b2dd-68c32e16b6ca" />
<img width="1515" height="849" alt="image" src="https://github.com/user-attachments/assets/e274d431-f161-4ee8-9e8a-071eb202f476" />
<img width="1516" height="852" alt="image" src="https://github.com/user-attachments/assets/a55622a5-5bad-4d79-be6d-9955b9ec85a6" />
<img width="1515" height="852" alt="image" src="https://github.com/user-attachments/assets/82ab23c5-c162-4495-a5d0-40bedc63d4ac" />



## 🔢 Key Findings
| Metric | Value |
|--------|-------|
| Total Revenue | ₹30.06 Cr |
| Total Orders | 10,000 |
| Avg Order Value | ₹30,061 |
| Gross Margin | 35.2% |
| Return Rate | 4.9% |
| Top Region | North India | ₹10.54 Cr (35.1%) |
| Top Category | Electronics | ₹18.91 Cr (62.9%) |
| Top Product | LapBook Air | ₹8.00 Cr |
| Best Channel | Online |

- Margins are flat at ~35% across most segments — pricing/discount strategy
  isn't materially differentiating profitability by category.
- Electronics leads revenue across every region.
- Repeat customers make up 46% of the customer base but drive 67% of total
  revenue, spending 2.4x more than one-time buyers.

## 🛠️ Repository Structure

```
├── powerbi/       Power BI .pbix file 
├── sql/           Business analysis queries (T-SQL)
├── dax/           DAX measures library
├── docs/          Dashboard blueprint & summary report
├── screenshots/   Dashboard page exports
└── data/          Sample dataset
```

## Author

**Manish Kumar** — Market Data Operations professional
[LinkedIn](https://linkedin.com/in/manish-kumar3112)
