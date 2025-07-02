# Generic_Profile_Scraper

## 🔧 Description

A Python-based, generic web scraper designed to extract structured profile data from paginated web directories. Demonstrates a full scraping workflow: pagination handling, HTML parsing, data extraction, and multi-format file output (CSV & JSON).

**Adaptable for:**
- Business directories
- Vendor listings
- Service provider profiles
- CRM data extraction
- General web data aggregation

---

## 💻 Features

- Automatically scrapes multi-page directories
- Extracts profile-level data from individual pages
- Outputs results in both CSV and JSON formats
- Written in Python (`requests`, `BeautifulSoup4`, `csv`, `json`)
- Clear data extraction logic for easy customization

---

## 🛠 Technologies Used

- Python 3.x
- requests
- beautifulsoup4
- csv / json (Python standard library)

---

## 🚀 Installation

1. Clone or download this repository.
2. Ensure Python 3 is installed.
3. Install required packages:
    ```bash
    pip install beautifulsoup4 requests
    ```
4. Run the scraper:
    ```bash
    python Generic_Scraper.py
    ```
5. Enter the starting URL of the site you wish to scrape when prompted.

---

## 🎯 Data Extracted

- Profile Name
- Location
- Profile Attribute 1
- Profile Attribute 2
- Profile Attribute 3
- Profile Attribute 4
- Service Rate (Local & Remote)
- Deposit Terms
- Cancellation Terms
- Contact Information

*Note: These fields are intentionally generalized for flexibility across multiple use cases.*

---

## 📄 License

Copyright (c) 2025 Couchtr26  
MIT License
