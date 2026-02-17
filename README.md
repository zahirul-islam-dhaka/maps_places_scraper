# Google Maps Places Scraper (Async Playwright)

This repository contains a Google Colab notebook and a Python script for
extracting publicly available business information from Google Maps search
results using Playwright (async).

The tool scrolls through Google Maps listings, opens individual place pages,
collects structured business data, and exports the results to a CSV or Excel
file for analysis and reporting.

---

## 🚀 Features

- Async scraping using Playwright (Chromium)
- Automated scrolling of Google Maps results panel
- Extraction of structured business details
- Handles dynamic page loading
- CSV / Excel export
- Works in Google Colab and local Python environments

---

## 📊 Data fields collected

- Business name  
- Address  
- Website  
- Phone number  
- Rating and review count  
- Opening time  
- Store shopping availability  
- In-store pickup  
- Delivery availability  
- Business type  
- Short business description  

---

## 📂 Repository contents

| File | Description |
|-----|-------------|
| `google_maps_places_scraper_async_zi.ipynb` | Google Colab notebook |
| `google_maps_places_scraper_async_zi.py` | Python script version |
| `Google Map Data Scrapped.xlsx` | Sample output dataset |
| `README.md` | Project documentation |

---

## ⚙️ Requirements

### Google Colab
No local setup required. Playwright runs inside Colab.

### Local Python
- Python 3.9+
- pandas
- playwright
- asyncio

Install dependencies:
```bash
pip install pandas playwright nest_asyncio
playwright install chromium
