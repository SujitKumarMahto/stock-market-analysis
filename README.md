# Stock Market Analysis Dashboard (IBM Coursera Project)

This project was completed as part of the IBM Data Science Professional Certificate on Coursera.

## 💼 Project Context

As a Data Scientist working for a fictional startup investment firm, the goal was to extract, analyze, and visualize stock price and revenue data for selected companies using real-world APIs and web scraping.

## 📊 Stocks Analyzed
- Tesla (`TSLA`)
- GameStop (`GME`)

## 📌 Tasks Covered

1. **Stock Data Extraction** using `yfinance`
2. **Revenue Data Web Scraping** using `requests` and `BeautifulSoup`
3. **Data Cleaning** and preparation for visualization
4. **KPI Dashboard** creation using `Plotly` and `make_subplots`
5. **Dynamic Visualizations** of stock price and revenue over time

## 📁 Folder Structure

- `notebooks/`: Jupyter Notebook with complete code for questions 1 to 6
- `data/`: Cleaned CSVs for stock and revenue data
- `images/`: Screenshots of code and output (for peer review or GitHub readme)
- `dashboard/`: Optional – If you export interactive HTML dashboards

## 📎 Technologies Used

- Python (Pandas, yfinance, BeautifulSoup, Plotly)
- Jupyter Notebook
- IBM Skills Network Labs
- IBM Watson Studio

## 📌 Sample Graph Function Used

```python
def make_graph(stock_data, revenue_data, stock):
    fig = make_subplots(rows=2, cols=1, shared_xaxes=True, subplot_titles=("Historical Share Price", "Historical Revenue"), vertical_spacing = .3)
    ...
    fig.show()
```

## ✅ Outcomes

- Clean visual comparison between share price trends and revenue movement for major tech stocks.
- Interactive dashboard demonstrating KPIs like stock performance and business growth patterns.

## 🏁 Completed

August 2025 – During M.Sc. in Data Science at MAHE (Manipal Academy of Higher Education)

---
