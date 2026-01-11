
---

# 📘 Book Price Intelligence System

This project is a multi-milestone system that builds a **smart book price intelligence platform** using:

* Web scraping
* Data cleaning and aggregation
* Sentiment analysis
* Similarity matching
* Cross-platform price comparison
* Rule-based price adjustment

The project is organized milestone-wise inside the `Notebooks/` directory.

---

## 📂 Project Structure

```
book-price-intelligence-system/
│
├── Notebooks/
│   ├── milestone_1_project_infrastructure/
│   │   ├── Milestone_1.ipynb
│   │   ├── input/
│   │   │   ├── input.jpg
│   │   │   ├── Data.npy
│   │   │   └── digit.png
│   │   └── README.md
│   │
│   ├── milestone_2_web_scraping_data_aggregation/
│   │   ├── Milestone_2.ipynb
│   │   ├── outputs/   # CSV & JSON from scraping
│   │   └── README.md
│   │
│   ├── milestone_3_sentiment_analysis/
│   │   ├── Milestone_3.ipynb
│   │   ├── outputs/
│   │   │   ├── COSINE_SIMILARITY/
│   │   │   ├── Sentiment_Analysis/
│   │   │   └── Getting_Authors_Popularity_Index_Reviews/
│   │   └── README.md
│   │
│   ├── milestone_4_cross_platform_integration/
│   │   ├── Milestone_4.ipynb
│   │   ├── outputs/
│   │   └── README.md
│
├── requirements.txt
├── License
└── README.md   ← (this file)
```

---

## 🚩 Milestone 1 – Project Infrastructure

**Folder:** `milestone_1_project_infrastructure/`
**Notebook:** `Milestone_1.ipynb`

### Purpose:

* Setup project environment
* Load and process input data
* Work with images and `.npy` files
* Build base processing pipeline

### Inputs:

* `input/input.jpg`
* `input/digit.png`
* `input/Data.npy`

### Output:

* Results shown in notebook (console / visual output)

---

## 🚩 Milestone 2 – Web Scraping & Data Aggregation

**Folder:** `milestone_2_web_scraping_data_aggregation/`
**Notebook:** `Milestone_2.ipynb`

### Purpose:

* Scrape product data from multiple pages
* Extract:

  * Product Name
  * Price
  * Category
* Save in structured formats

### Outputs (inside `outputs/`):

* `products_all_pages.csv/json`
* `products_ajax.csv/json`
* `phones_simple.csv/json`
* `tablets_all_pages.csv/json`
* `touch_phones_all_pages.csv/json`

---

## 🚩 Milestone 3 – Sentiment & Similarity Analysis

**Folder:** `milestone_3_sentiment_analysis/`
**Notebook:** `Milestone_3.ipynb`

### Purpose:

* Analyze sentiment from reviews and news
* Match books with related news using cosine similarity
* Adjust pricing using sentiment and popularity

### Output Sections:

#### 1) COSINE_SIMILARITY

* Books data
* News data
* Book–news similarity results
* Final pricing after similarity

#### 2) Sentiment_Analysis

* Scraped books
* News headlines
* Sentiment-adjusted pricing

#### 3) Author Popularity Index

* Detect authors
* Recover missing authors
* Generate popularity index
* Merge ratings

All results are saved in both **CSV and JSON**.

---

## 🚩 Milestone 4 – Cross Platform Integration

**Folder:** `milestone_4_cross_platform_integration/`
**Notebook:** `Milestone_4.ipynb`

### Purpose:

* Combine all previous results
* Clean book data
* Find ISBN
* Scrape competitor prices
* Compare prices
* Apply rule-based price adjustment

### Outputs:

* `books_raw_data.csv/json`
* Cleaned books
* ISBN found / not found
* Competitor prices
* Final price comparison
* Rule-based price adjustments

---

## ▶ How to Run

1. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

2. Open Jupyter:

   ```bash
   jupyter notebook
   ```

3. Run notebooks in order:

   ```
   Milestone_1.ipynb
   Milestone_2.ipynb
   Milestone_3.ipynb
   Milestone_4.ipynb
   ```

---

## 🧰 Technologies Used

* Python
* Jupyter Notebook
* Pandas, NumPy
* BeautifulSoup, Requests
* NLP & ML Libraries

---

## 🎯 Final Outcome

This system:

* Scrapes book and product data
* Analyzes sentiment from reviews & news
* Matches books with trending topics
* Compares competitor prices
* Suggests intelligent price adjustments

---

## 👨‍💻 Author

**Gaddam Sathvik Reddy**
Project developed for Infosys Springboard program using AI, Web Scraping, NLP, and Data Analytics.
