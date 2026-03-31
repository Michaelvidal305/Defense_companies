# 🛡️ Global Defense Companies Analysis

## 📌 Project Overview
This repository analyzes the Top 100 Defense Companies (2023) using SIPRI data, enriched with:

  - **Country‑level geopolitical classifications** (G7, G20, NATO, EU, income level, continent)

  - **Historical stock price data** for publicly listed defense companies

The goal is to build a **full SQL‑driven analytics workflow** that answers:

  - Which countries dominate global defense revenue?

  - How concentrated is the defense industry?

  - Which companies grew the fastest year‑over‑year?

   - How do geopolitical alliances correlate with defense presence?

   - How do income levels relate to defense industry participation?

   - How do defense companies perform in the stock market over time?

This project is designed to showcase **data cleaning, SQL exploration, KPI creation, and analytical storytelling.**

## 📁Repository Structure

MLB_Batting_stats/
│── 📂 Dataset/              # Raw MLB batting data
│── 📂 cleaned_dataset/      # Cleaned CSVs after SQL processing
│── 📂 Data_exploration/     # SQL scripts, joins, lookup tables
│── 📂 visuals/              # Plots, charts, exports
│── 📄 README.md             # Project documentation


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
| Arms Revenue percentage | Share of total revenue from defense |
| Arms Revenue Growth Percentage | Year-to-year revenue percentage gain/loss |
| Rank Change | Year-to-year rank gain/loss |
| Arms Revenue Growth USD | Year-to-year revenue gain/loss (USD millions) |
| Industry | Company's indurty name |

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

3. Stock Price History
- Daily OHLCV data for publicly listed defense companies:

| Column | Description                                                       |
|--------|-------------------------------------------------------------------|
| Date | The trading date |
| Close | The closing price of the stock on that day |
| High | The highest price of the stock on that day |
| Low | The lowest price of the stock on that day |
| Open | The opening price of the stock on that day |
| Volume | The number of shares traded on that day |
| Company name | The name of the listed company |

**File:** [Stock Price History.csv](https://github.com/Michaelvidal305/Defense_companies/blob/main/Dataset/Stock%20Price%20History.csv)

## 🧠 Key Questions This Project Can Answer
**Company‑Level**
  - Who are the largest defense contractors globally?

  - Which companies grew the fastest in arms revenue?

  - How dependent is each company on defense vs. civilian revenue?

  - Which industries dominate the defense sector?

**Country‑Level**
  - Which countries host the most defense companies?

  - How do NATO / G7 / G20 members compare?

  - How does income level relate to defense industry presence?

**Stock‑Level**
  - Which companies show the strongest long‑term uptrend?

  - Which companies are most volatile?

  - How do stock returns compare across regions?

## 🛠️ Analysis Performed

**SIPRI Dataset**
  - Market share calculations

  - HHI concentration index

  - Arms revenue dependency score

  - Rank change analysis

  - Country‑level revenue aggregation

**Country Dataset**
  - Continent‑level segmentation

  - Alliance membership scoring

  - Income‑level comparisons

  - Geopolitical alignment index

**Stock History Dataset**
  - Daily returns

  - Average return per company

  - Volatility (std dev of returns)

  - Best/worst trading days

  - Year‑over‑year price growth

  - Trend classification (Uptrend / Downtrend / Flat)

## 📈Visualization Ideas

  - **Bar charts:** Top 10 companies by arms revenue

  - **Choropleth map:** Arms revenue by country

  - **Scatter plot:** Arms revenue % vs. total revenue

  - **Line charts:** Stock price trends

  - **Heatmaps:** Geopolitical alignment scores

## 🚀 Future Enhancements
  - Merge SIPRI + country + stock datasets into a unified analytical model

  - Build a dashboard (Tableau / Power BI / Python)

  - Add machine learning for revenue growth prediction

  - Add clustering for geopolitical grouping

## 👤 Author
Michael Vidal  
Data Analyst | SQL | Data Cleaning | Visualization
