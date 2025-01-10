# Amazon Web Scrapping & Price Tracker 

This project is an Amazon Web Scraper built in Python that tracks product prices and stores the data in a CSV file. It can be used to monitor price changes over time for specific Amazon products.

## Features

- Extracts the product title and price from an Amazon product page.
- Saves the data to a CSV file with timestamps for tracking.
- Handles data cleaning and formatting for readability.
- Supports repeated price checks with a delay to avoid overloading the server.

## How It Works

1. **Web Scraping**: The script uses `BeautifulSoup` to parse the HTML content of the Amazon product page.
2. **Data Cleaning**: Extracted price and title are cleaned and formatted.
3. **Data Storage**: The data is stored in a CSV file for easy analysis using tools like Excel or Pandas.
4. **Automation**: The script can run periodically to check for price updates.

## Prerequisites

- Python 3.x
- Required Python libraries:
  - `BeautifulSoup4`
  - `requests`
  - `pandas`
  - `csv`
  - `re`
