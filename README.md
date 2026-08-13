# Web Scraping with Python: Extracting Structured Data from Web Pages

## Project Overview

This project documents my practical introduction to **web scraping with Python** and the process of turning information stored in webpages into structured data.

The work progressed from understanding HTML and extracting individual webpage elements to scraping HTML tables, cleaning the extracted content, creating a Pandas DataFrame, and exporting the resulting dataset to CSV.

### Workflow

**Webpage → HTTP request → HTML → BeautifulSoup → Element/Table extraction → Text cleaning → Pandas DataFrame → CSV**

## Learning Objectives

- Understand the structure of webpages using HTML.
- Retrieve webpage content with `requests`.
- Parse HTML with `BeautifulSoup`.
- Locate elements using `find()` and `find_all()`.
- Extract and clean text from HTML elements.
- Identify and extract HTML tables.
- Convert scraped rows into a Pandas DataFrame.
- Export structured data to CSV.

## Tools & Technologies

| Tool | Purpose |
|---|---|
| Python | Programming language |
| Requests | Sending HTTP requests and retrieving webpage content |
| BeautifulSoup | Parsing and navigating HTML |
| Pandas | Structuring extracted data into a DataFrame |
| Jupyter Notebook | Development and documentation environment |

## Data Sources Used in the Exercises

The notebook contains practical exercises using:

- **Scrape This Site** — introductory HTML element extraction
- **Worldometer** — table and column-header extraction
- **Wikipedia** — extraction of a table containing U.S. companies by revenue

The notebook is based on the exercises completed during my Python/data analysis training.

## Project Process

### 1. Understanding HTML

I first explored webpage structure and worked with elements such as:

- `div`
- `p`
- `class`
- `table`
- `th`
- `tr`
- `td`

### 2. Sending HTTP Requests

The `requests` library was used to retrieve webpage HTML.

### 3. Parsing HTML

BeautifulSoup was used to parse the returned HTML and make the webpage structure easier to navigate.

### 4. Finding Specific Elements

I practiced using `find()` and `find_all()` to locate specific HTML elements and classes.

### 5. Extracting and Cleaning Text

Text was extracted from HTML elements and cleaned using `.strip()` to remove unnecessary whitespace.

### 6. Scraping Tables

I located HTML tables and extracted:

- Table headers
- Table rows
- Individual table cells

### 7. Structuring the Data

The scraped records were organized into a Pandas DataFrame.

The extraction process also included handling rows whose number of values did not exactly match the expected number of columns.

### 8. Exporting the Data

The resulting DataFrame was prepared for CSV export so that the scraped information could be used as a standalone dataset.

## Key Learning Outcomes

This project strengthened my understanding of:

- HTML structure
- HTTP requests
- HTML parsing
- Webpage element selection
- Text extraction and cleaning
- HTML table extraction
- Data structuring with Pandas
- CSV data export

## Repository Structure

```text
web-scraping-with-python/
│
├── web_scraping_with_python.ipynb
├── README.md
├── requirements.txt
└── .gitignore
```

## Installation

Clone the repository and install the required Python libraries:

```bash
pip install -r requirements.txt
```

Then open:

```bash
web_scraping_with_python.ipynb
```

in Jupyter Notebook or JupyterLab.

## Note

This project represents a learning exercise in Python-based web scraping and data acquisition. The scraped information should be treated in accordance with the terms, policies, and access rules of the relevant websites.

## Author

**Eniola Adelakun Zainab**

Aspiring Data Analyst | Python | SQL | Excel | Power BI | Tableau
