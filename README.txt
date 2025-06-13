# Generic Profile Scraper - Codex Libris Mechanicus Data Module

## 🔧 Description

A Python-based generic web scraper designed to extract structured profile data from paginated web directories. This tool demonstrates full scraping workflow: pagination handling, HTML parsing, data extraction, and multi-format file output (CSV & JSON).

This tool can be adapted for:

- Business directories
- Vendor listings
- Service provider profiles
- CRM data extraction
- General web data aggregation

---

## 💻 Features

- Handles multi-page scraping automatically
- Extracts profile-level data from individual pages
- Outputs results into both CSV and JSON formats
- Fully written in Python using requests, BeautifulSoup, csv, and json modules
- Clean separation of data extraction logic for easy modification

---

## 🛠 Technologies Used

- Python 3.x
- Requests
- BeautifulSoup4
- CSV / JSON (standard library)

---

## 🚀 Installation

1. Clone or download this repository.
2. Ensure Python 3 is installed.
3. Install BeautifulSoup4 if not already installed:

```bash
pip install beautifulsoup4
Run the scraper:

bash
Copy
Edit
python Generic_Scraper.py
Enter the starting URL of the site you wish to scrape when prompted.

🎯 What This Scraper Extracts
Profile Name

Location

Profile Attribute 1

Profile Attribute 2

Profile Attribute 3

Profile Attribute 4

Service Rate (Local & Remote)

Deposit Terms

Cancellation Terms

Contact Information

Note: These fields are intentionally generalized to fit multiple potential use cases.