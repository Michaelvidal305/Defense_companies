# 🛡️ Global Defense Companies Analysis

## 📌 Project Overview
This project analyzes the Top 100 Defense Companies (2023) using data from SIPRI, combined with a country‑level geopolitical classification dataset.
The goal is to explore:

  - Global distribution of defense contractors
  - Arms revenue trends
  - Country‑level defense industry characteristics
  - G7 / G20 / NATO / EU participation
  - Regional and economic segmentation
  - Year‑over‑year ranking changes

This repository is structured for data analysis, visualization, and future modeling.

## 📁 Datasets Included

1. SIPRI Top 100 Defense Companies (2023)
- This dataset allows analysis of **growth, market share, and geopolitical distribution**
  
| Column | Description                                                       |
|--------|-------------------------------------------------------------------|
| Rank (2023) | Company's global ranking in 2023 |
| Rank (2022) | Previous year ranking |
| Company name | Official company name |
| Country | Country of headquarters |
| Arms Revenue 2023 | Arms-related revenue (USD millions) |
| Arms Revenue 2022 | Previous year arms revenue (USD millions) |
| Total Revenue 2023 | Total coporate revenue (USD millions) |
| Arms Revenue | Share of total revenue from defense |

**File:** [SIPRI Top 100 Defense Companies (2023).csv](https://github.com/Michaelvidal305/Defense_companies/blob/main/Dataset/SIPRI%20Top%20100%20Defense%20Companies%20Official%20List.csv)


2. Country‑Level Segmentation Dataset
- This dataset is used to enrich the company list with **geopolitical attributes**

| Column | Description                                                       |
|--------|-------------------------------------------------------------------|
| Country | Nation name |
| Continent | Geographic region |
| Income Level | World Bank income classification |
| G7 | Whether the country is a G7 member |
| G20 | Whether the country is a G20 member |
| NATO | Whether the country is a NATO member |
| EU | Whether the country is a EU member |

**File:** [Country Segmentation Dataset.csv](https://github.com/Michaelvidal305/Defense_companies/blob/main/Dataset/Listed%20Companies%20CountryWise%20%20Segregation.csv)

## 🧠 Key Questions This Project Can Answer
  - Which countries dominate global defense revenue?
  - How concentrated is the defense industry among the top firms?
  - Which companies grew the fastest year‑over‑year?
  - What percentage of revenue comes from arms vs. civilian sectors?
  - How do geopolitical alliances (NATO, G7, G20) correlate with defense spending?
  - How do income levels relate to defense industry presence?

## 🛠️ Planned Analysis
1. Company‑Level Analysis
   - Revenue growth (2022 → 2023)
   - Market share of top 10 vs. rest
   - Arms revenue dependency (% of total revenue)

2. Country‑Level Analysis
   - Number of companies per country
   - Total arms revenue by country
   - NATO vs. non‑NATO comparison
   - G7 vs. G20 segmentation

3. Visualization Ideas
   - Bar charts of top companies
   - Choropleth map of arms revenue by country
   - Scatter plot: Total revenue vs. arms revenue %
   - Ranking change visualization (2022 → 2023)
