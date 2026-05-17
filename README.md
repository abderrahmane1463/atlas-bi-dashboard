<h1 align="center">Atlas Office Supplies — Business Intelligence Dashboard</h1>

<p align="center">
  <em>Interactive BI dashboard transforming 9,994 sales records into strategic insights on revenue, profit, and regional performance</em>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10+-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
  <img src="https://img.shields.io/badge/Plotly-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white"/>
</p>

<p align="center">
  <a href="https://atlas-bi-dashboard-be4xuhv73dtmzvbyzzuh2h.streamlit.app/">
    <strong>View Live Dashboard</strong>
  </a>
</p>

---

## Overview

A business intelligence dashboard for Atlas Office Supplies & Furniture — a company providing modern workspace solutions. Built on 9,994 transactional records, the dashboard surfaces four core KPIs (Sales, Profit, AOV, Customer Count) and answers strategic questions around seasonality, regional health, customer segment profitability, and logistics impact through interactive Plotly visualisations.

## Features

- Core KPIs: Total Sales, Total Profit, Average Order Value (AOV), and unique Customer Count
- Year-over-Year revenue trend chart identifying Q3/Q4 seasonal peaks
- Regional performance map highlighting high-sales regions and underperforming states
- Customer segment profitability analysis — exposing segments with high revenue but poor margins
- Shipping cost and delivery method impact on customer satisfaction and profitability
- Fully branded UI following Atlas's official color palette (Primary Blue, Accent Orange, Neutral Gray)

## Tech Stack

| Category | Tools |
|----------|-------|
| Language | Python |
| Dashboard | Streamlit |
| Visualisation | Plotly, Matplotlib, Seaborn |
| Data Analysis | pandas, numpy |
| Deployment | Streamlit Community Cloud |

## Getting Started

```bash
git clone https://github.com/abderrahmane1463/atlas-bi-dashboard.git
cd atlas-bi-dashboard
pip install -r requirements.txt
streamlit run atlas_dashboard.py
```

## Project Structure

```
atlas-bi-dashboard/
├── atlas_dashboard.py      # Main Streamlit application
├── Atlas.csv               # Sales dataset (9,994 records)
├── atlas_project.ipynb     # Exploratory analysis notebook
└── requirements.txt
```

## Results / Key Insights

- Q3 and Q4 consistently outperform other quarters, making inventory management around these seasons a key operational lever
- Certain customer segments generate high sales volume but deliver below-average profit margins, pointing to unsustainable discounting practices
- Shipping costs represent a meaningful drag on profitability in specific regions, suggesting a case for carrier renegotiation or delivery method optimisation

---

<p align="center">Made by <a href="https://github.com/abderrahmane1463">Cherfaoui Houssam Abderrahmane</a></p>
