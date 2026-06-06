# Web Scraping & Text Analytics Pipeline 📊

A Python-based pipeline that scrapes articles from the web 
and performs in-depth text analysis including sentiment 
scoring, readability metrics, and linguistic feature extraction.

## 🛠️ Tech Stack
- **Scraping:** BeautifulSoup, Requests
- **Analysis:** NLTK, Pandas
- **Output:** Excel reports (openpyxl)

## ✨ What It Does
- Scrapes article content from URLs
- Extracts sentiment scores (positive/negative)
- Computes readability scores (FOG index, avg sentence length)
- Generates structured Excel report of all metrics

## 📁 Structure
├── data/       # Input URLs and reference files
├── scripts/    # Scraping and analysis scripts  
├── outputs/    # Extracted text + final Excel output

## 🚀 How to Run
pip install requests beautifulsoup4 pandas nltk openpyxl
python scripts/extract.py
python scripts/analyze.py
