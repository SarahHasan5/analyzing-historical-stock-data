# analyzing-historical-stock-data
This project is part of the IBM Data Science Professional Certificate.
It focuses on extracting, cleaning, and visualizing historical stock and revenue data for companies like Tesla and GameStop using Python.
The final result is an interactive dashboard that shows both stock price trends and company revenue growth over time.

🚀 Project Overview:

In this project, I used:
yfinance → to download historical stock data from Yahoo Finance
BeautifulSoup → to scrape revenue data from HTML pages
pandas → for data cleaning and manipulation
plotly → to create interactive visualizations
The main goal was to compare how stock prices correlate with the company’s quarterly revenue, and to visualize these trends side by side.

🧠 Key Steps

Data Extraction
Used yfinance.Ticker() to obtain stock data for Tesla (TSLA) and GameStop (GME)
Scraped quarterly revenue tables from web pages using requests and BeautifulSoup
Data Cleaning
Converted text-based revenue values to numeric format
Removed unnecessary symbols and empty rows
Data Visualization
Used a custom make_graph() function to plot:
Stock Price (Top Chart)
Revenue (Bottom Chart)
Restricted visualizations to data before June 2021

| Library         | Purpose                    |
| --------------- | -------------------------- |
| `yfinance`      | Fetching stock market data |
| `requests`      | Downloading web page HTML  |
| `BeautifulSoup` | Web scraping tables        |
| `pandas`        | Data manipulation          |
| `plotly`        | Interactive visualization  |
