# Tesla & GameStop: Stock Price vs. Revenue Dashboard

Python project that extracts stock price data and quarterly revenue for Tesla (TSLA) and GameStop (GME), then plots them together to compare market performance with business fundamentals.

## Dataset
- **Stock prices:** daily history pulled with the `yfinance` library (Date, Open, High, Low, Close, Volume).
- **Revenue:** quarterly revenue web-scraped from HTML pages using `requests` and `pandas.read_html`.

## Tools Used
Python, pandas, yfinance, requests, BeautifulSoup, matplotlib

## What the Notebook Does
1. Downloads full stock history for TSLA and GME
2. Scrapes and cleans quarterly revenue tables (removes `$` and `,`, drops empty rows)
3. Builds a two-panel chart per company: share price on top, revenue below

## Key Insights
- Tesla's quarterly revenue grew from about $31M (Q3 2010) to about $21.5B (Q3 2022).
- Tesla's Q3 2022 revenue was roughly 56% higher than Q3 2021.
- GameStop's revenue is seasonal, peaking in the holiday quarter.
- GameStop's revenue declined about 34% between Apr 2019 and Apr 2020.

## How to Run
Open `revenue_dashboard.ipynb` in Jupyter Notebook or Google Colab and run all cells.
