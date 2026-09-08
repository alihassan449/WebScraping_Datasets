# WebScraping_Datasets

This repository contains two datasets generated as part of the FAST-NU Web Scraping assignment.  
Both datasets were collected entirely through Python scrapers (Requests + BeautifulSoup for static content, Selenium for dynamic content).  
No manual edits were made — the CSVs are exactly what the scrapers produced.

## 📂 Datasets

- 23L_0916_versionB_static_books.csv
  - Source: [Books to Scrape](https://books.toscrape.com/)  
  - Categories scraped: Travel, Mystery, Classics, Historical Fiction  
  - Fields: Title, Price, Availability, Star Rating (numeric), UPC, Description, Category  

- 23L_0916_versionB_dynamic_quotes.csv 
  - Source: [Quotes to Scrape (scroll)](https://quotes.toscrape.com/scroll)  
  - Collected via Selenium with infinite scrolling  
  - Fields: Quote text, Author name, Tags, Number of tags, Scroll batch  

## ✅ Verification
- Static scraper: Counts matched site totals (PASS for all categories).  
- Dynamic scraper: Collected 100 quotes, stopped after two empty scrolls (complete dataset).  

---

### Author
Ali — FAST School of Computing, FAST-NU Lahore
