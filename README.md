# Web Scraping Project

A Python-based web scraping tool designed to extract product data from e-commerce websites (like Amazon) and static pages. This project demonstrates how to handle dynamic content, bypass bot detection, and save data into structured formats.

## Project Structure

- *selenium.py (or spy.py): The main script using **Selenium WebDriver* to scrape dynamic websites (e.g., Amazon.in). It includes "Stealth Mode" features to bypass bot detection.
- *beautifulsoup.py: A script using **BeautifulSoup* for scraping static HTML pages (lighter and faster).
- *visualization.py*: (Optional) Script to visualize the scraped data (e.g., price comparisons).
- *database.py*: Handles connections to SQLite for storing data.

## Features

- *Dynamic Scraping*: Uses Selenium to render JavaScript and interact with pages.
- *Stealth Mode*: Includes custom User-Agents and disables automation flags to avoid "503 Service Unavailable" errors.
- *Data Export*: Automatically saves scraped data to:
  - CSV (products_output.csv)
  - Excel (products_output.xlsx)
  - SQLite Database (products_db.sqlite)
- *Error Handling*: Robust checks for missing elements or empty data.

## Technologies Used

- *Python 3.x*
- *Selenium*: For browser automation.
- *BeautifulSoup4*: For parsing HTML.
- *Pandas*: For data manipulation and saving files.
- *OpenPyXL*: For writing Excel files.
- *SQLite3*: For database storage.
- *WebDriver Manager*: For automatic Chrome driver management.

## Installation

1. *Clone the repository:*
   ```bash
   git clone [https://github.com/harinvc/web-scrapping-.git](https://github.com/harinvc/web-scrapping-.git)
   cd web-scrapping-
