# Python Web Scraping Projects

This repository contains multiple Python projects for practicing web scraping using `requests` and `BeautifulSoup`.  
Each project extracts useful information from real websites and saves the data in CSV files or downloads images.

---

## 📂 Projects

### 1. Books Page 1 Scraper
- Scrapes book titles, prices, and availability from the first page of [Books to Scrape](https://books.toscrape.com/).
- Output: `books_page1.csv`

### 2. Books All Pages Scraper
- Scrapes all books across all pages of the site.
- Output: `books_all.csv`

### 3. Categories Scraper
- Extracts all book categories and their URLs.
- Output: `categories.csv`

### 4. Cheap Books Scraper
- Scrapes books cheaper than £20 across 50 pages.
- Output: `cheap_books.csv`

### 5. Book Images Downloader
- Downloads the first 20 book images and saves them locally.

### 6. BBC Tech News Scraper
- Extracts technology news titles, URLs, and summaries from BBC News.
- Output: `bbc_tech_news.csv`

---

## ⚙️ Requirements

Install dependencies with:
```bash
pip install requests beautifulsoup4 lxml

