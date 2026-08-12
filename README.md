# Web-data-extraction-and-analysis
Web Data Extraction and Analysis using Python (BeautifulSoup &amp; Requests) with automated CSV exports and Seaborn visual analytics for CodSoft Internship Task 5.
# 🌐 CodSoft Data Analytics Internship - Task 5: Web Data Extraction & Analysis

## 📌 Project Overview
This repository contains **Task 5** for the CodSoft Data Analytics Internship. The project demonstrates end-to-end web scraping using **BeautifulSoup** and **requests** to extract structured e-commerce book data from a public sandbox web source (`books.toscrape.com`).

---

## 🛠️ Technical Workflow & Features
1. **Automated Scraping Engine:** Fetches pagination links and extracts HTML tags for titles, numeric GBP prices, star ratings, and stock availability.
2. **Data Cleaning & Structuring:** Parses raw text elements into a clean Pandas DataFrame (converting string ratings like "Three" to numeric values `3`).
3. **Exploratory Visualizations:** Seaborn boxplots and countplots analyzing pricing variations across rating tiers.
4. **⭐ Bonus Automation:** Exports the final structured dataset automatically to `scraped_books_data_task5.csv`.

---

## 📊 Summary Insights
* **Extracted Records:** Multi-page data extraction compiled successfully.
* **Pricing Dynamics:** Price ranges across star rating tiers remain relatively uniform, indicating minimal pricing premiums on higher-rated titles.

---

## 🧰 Tech Stack
* **Language:** Python 3
* **Libraries:** `requests`, `beautifulsoup4`, `pandas`, `matplotlib`, `seaborn`
* **Environment:** Google Colab
*
