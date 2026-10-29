# Python Web Scraping & Quotes Analysis

A Python-based web scraping and data analysis project built using **Requests, BeautifulSoup, Pandas, and Matplotlib**. The project demonstrates how to collect structured information from web pages, automate pagination, process extracted data, and visualize meaningful insights.

## Project Overview

This project extracts quotes and author information from [Quotes to Scrape](https://quotes.toscrape.com/), a publicly available website designed for web scraping practice.

The primary focus is on **Python programming, automated data extraction, data processing, and exploratory analysis**, rather than website development.

## Key Features

- **Automated Web Scraping:** Extracts quotes and author names using Requests and BeautifulSoup.
- **Automatic Pagination:** Navigates through multiple pages to collect 100 quotes.
- **Structured Data Export:** Saves extracted records in CSV format.
- **Data Quality Checks:** Identifies missing values and duplicate records.
- **Data Analysis:** Analyzes quote frequency across authors.
- **Data Visualization:** Generates a bar chart of the 10 most frequently appearing authors.
- **Search Functionality:** Supports author-name and keyword-based quote searches.
- **Modular Code:** Uses reusable Python functions for scraping and data extraction.

## Technologies Used

| Technology | Purpose |
|---|---|
| Python | Core programming language |
| Requests | Fetching web page content |
| BeautifulSoup4 | HTML parsing and data extraction |
| Pandas | Data processing and analysis |
| Matplotlib | Data visualization |
| Jupyter Notebook | Development and experimentation |

## Project Structure

```text
python-quotes-web-scraping/
├── Web_Scraping_Practice.ipynb
├── final_quotes_dataset.csv
├── top_10_authors.png
├── README.md
└── .gitignore
```

## Dataset Summary

The final dataset contains 100 extracted quotes with the following columns:

| Column | Description |
|---|---|
| Quote | Extracted quotation text |
| Author | Name of the quote's author |

**Data Quality Results**

| Metric | Result |
|---|---|
| Total Records | 100 |
| Missing Values | 0 |
| Duplicate Records | 0 |

## Data Visualization

The following chart shows the top 10 authors based on the number of quotes appearing in the extracted dataset.

![Top 10 Authors by Quote Frequency](top_10_authors.png)

## Installation & Usage

**1. Clone the repository**

```bash
git clone https://github.com/saqlainsaqlain625/python-quotes-web-scraping.git
cd python-quotes-web-scraping
```

**2. Install the dependencies**

```bash
pip install requests beautifulsoup4 pandas matplotlib notebook
```

**3. Launch Jupyter Notebook**

```bash
jupyter notebook
```

Open `Web_Scraping_Practice.ipynb` and run the cells in order.

## Learning Outcomes

Through this project, I practiced:

- Sending HTTP requests and parsing HTML documents.
- Extracting structured information using BeautifulSoup.
- Implementing loops and automatic pagination.
- Working with Python lists, dictionaries, and functions.
- Processing and exporting datasets with Pandas.
- Performing basic exploratory data analysis.
- Creating visualizations using Matplotlib.
- Implementing reusable search functions.

## Data Source

**[Quotes to Scrape](https://quotes.toscrape.com/)**

An educational website specifically designed for practicing web scraping. The website is used solely as a data source; its design and development are not part of this project.

## Project Scope

This is a beginner-level Python project developed for hands-on learning and portfolio demonstration. It focuses on fundamental web scraping techniques, structured data extraction, and basic data analysis.

---

**Developed by [Saqlain Mushtaq](https://github.com/saqlainsaqlain625)**
