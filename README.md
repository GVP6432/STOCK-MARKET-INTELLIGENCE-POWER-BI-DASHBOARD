# Stock Market Intelligence — Power BI Dashboard

An interactive Power BI analytics project exploring historical stock performance, risk, and trading activity across five real-estate companies listed in India.

## Project Overview

This dashboard analyses historical stock market data to compare company performance, evaluate risk, and identify unusual trading activity through interactive visualizations and DAX measures.

### Companies Analysed

- DLF
- Godrej Properties
- Lodha
- Oberoi Realty
- Sobha

### Analysis Period

January 2013 – January 2026, subject to available records.

## Dashboard Pages

1. **Project Cover** — Project introduction and portfolio links.
2. **Executive Overview** — Returns, normalized performance, volatility, and maximum drawdown.
3. **Trading Activity & Market Insights** — Trading volume, turnover, monthly trends, and volume spikes.
4. **Project Methodology & Insights** — Data overview, KPI methodology, key findings, and limitations.

## Key Metrics

- Period Return
- Annualized Volatility
- Maximum Drawdown
- Total Trading Volume
- Total Turnover
- Average Daily Volume
- Volume Spike Ratio
- Normalized Performance Index

## Tools & Technologies

- Microsoft Power BI
- DAX
- Power Query
- Data Modeling
- CSV datasets
- JSON Power BI theme

## Project Structure

```text
STOCK-MARKET-INTELLIGENCE/
├── DASHBOARD/
│   └── STOCKS.pbix
├── DATA/
│   ├── DLF.csv
│   ├── GODREJ.csv
│   ├── LODHA.csv
│   ├── OBEROI.csv
│   └── SOBHA.csv
├── IMAGES/
│   ├── Neon GitHub Octocat Emblem.png
│   ├── Neon LinkedIn Icon on Tech Platform.png
│   └── Neon Skyline Growth Emblem.png
├── stock_market_intelligence_cyber_neon.json
├── .gitignore
└── README.md
```

## Methodology

The project uses historical closing prices, previous closing prices, trading volume, and turnover to calculate performance and risk indicators.

- **Period Return:** Percentage change between the first and last available closing prices in the selected period.
- **Annualized Volatility:** Standard deviation of daily returns multiplied by the square root of 252.
- **Maximum Drawdown:** Largest peak-to-trough decline during the selected period.
- **Volume Spike Ratio:** Daily trading volume compared with the company's average daily volume baseline.

## Limitations

- Findings depend on the accuracy and completeness of the source data.
- Results vary with the selected date range and company.
- Unusual volume does not, by itself, explain why trading activity occurred.
- Historical performance does not guarantee future returns.

## Disclaimer

This project is for educational and analytical purposes only. It is not investment advice or a recommendation to buy or sell any security.
