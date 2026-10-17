# Quote-Scraper-Analytics
Python web scraping project that extracts quotes, authors, and tags using Requests, BeautifulSoup, and Pandas.
# Quote Scraper Analytics

A Python web scraping project that collects quotes, authors, and tags from the Quotes to Scrape website using Requests, BeautifulSoup, and Pandas.

## Features

- Fetch webpage content using Requests.
- Parse HTML using BeautifulSoup.
- Extract quotes and author names.
- Collect tags associated with each quote.
- Display the extracted information in a Pandas DataFrame.
- Export the collected data to a CSV file.

## Technologies Used

- Python
- Jupyter Notebook
- Requests
- BeautifulSoup4
- Pandas

## Target Website

https://quotes.toscrape.com/

This website provides sample content for practicing web scraping.

## Installation

Install the required libraries:

```bash
pip install -r requirements.txt
```

## How to Run

1. Clone this repository.
2. Open `quote analytics.ipynb` in VS Code or Jupyter Notebook.
3. Run the notebook cells in order.
4. View the extracted quotes, authors, and tags.
5. Find the generated `quotes.csv` file in the working directory.

## Project Structure

```text
quote-scraper-analytics/
├── quote analytics.ipynb
├── README.md
├── requirements.txt
├── .gitignore
└── quotes.csv
```

The CSV file is generated when the notebook runs successfully.

## Learning Objectives

- Understand HTTP requests and response status codes.
- Learn HTML parsing with BeautifulSoup.
- Extract structured data from web pages.
- Use Pandas to organize data.
- Export data to CSV format.

## Author

Add your name and GitHub profile here.

## Disclaimer

This project is intended for educational purposes. Respect the target website's terms of use and scraping policies.
