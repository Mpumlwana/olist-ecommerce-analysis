# 🛒 Olist E-Commerce Sales Analysis

## Project Overview
End-to-end data analysis of 100,000+ real Brazilian e-commerce orders 
from Olist, covering data cleaning, SQL analysis, and interactive 
Power BI dashboard.

## Business Questions Answered
- What is the total revenue and monthly growth trend?
- Which product categories generate the most revenue?
- Which Brazilian states have the most customers?
- How is delivery performance across different states?
- What do customers think? (review score analysis)

## Key Findings
| Metric | Value |
|--------|-------|
| Total Revenue | R$19.8 Million |
| Total Delivered Orders | 96,478 |
| Average Delivery Time | 12.1 days |
| Late Order Rate | 7.8% |
| Average Review Score | 4.1 / 5 |
| Top Revenue Category | Bed & Bath (R$1.69M) |
| Top Revenue State | São Paulo (37% of revenue) |

## Tools & Technologies
| Tool | Purpose |
|------|---------|
| Python (Pandas, NumPy) | Data cleaning & EDA |
| Jupyter Notebook | Exploratory analysis |
| SQLite + DBeaver | SQL business analysis |
| Power BI Desktop | Interactive dashboard |
| Git + GitHub | Version control |

## Project Structure

## Dashboard Pages
1. **Executive Summary** — KPI cards (Revenue, Orders, Delivery, Reviews)
2. **Category Performance** — Top 15 revenue categories bar chart
3. **Geographic Analysis** — Brazil bubble map by state revenue
4. **Customer Satisfaction** — Review score distribution

## Dataset
- Source: [Olist Brazilian E-Commerce Dataset](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce)
- Size: ~100,000 orders across 9 relational tables
- Period: 2016 - 2018

## How to Run
1. Clone this repository
2. Download the dataset from Kaggle and place CSVs in `data/raw/`
3. Run notebooks in order (01 → 02 → 03)
4. Open `powerbi/olist_dashboard.pbix` in Power BI Desktop

## Author
**Mpumlwana Lakhikhaya**    
[GitHub](https://github.com/Mpumlwana)