# web-table-scraper
A Python notebook for scraping structured tables from websites using BeautifulSoup and pandas.
# Web Table Scraper

This repository contains a Jupyter Notebook that demonstrates how to scrape structured HTML tables from websites using Python.

## 📘 Features

- Scrapes tables from a given webpage
- Uses `requests`, `BeautifulSoup`, and `pandas`
- Parses HTML table structure and converts to DataFrame
- Supports exporting data to CSV

## 🧰 Technologies Used

- Python
- Jupyter Notebook
- BeautifulSoup (bs4)
- pandas
- requests

## 📄 File Description

### `Scraping a Table from a Website.ipynb`

This notebook walks through the steps to:
1. Request and parse a webpage
2. Locate the HTML `<table>` element(s)
3. Extract headers and row data
4. Convert to a DataFrame
5. Export as CSV or view in notebook

## 🚀 How to Run

1. Install dependencies:
   ```bash
   pip install requests beautifulsoup4 pandas
