# Notebook Sections: Inputs and Outputs Mapping

This document maps each major heading in the notebook to its corresponding inputs and generated outputs.

---

# 1. Sentiment Analysis

## A. Playwright-Based Book Scraper

### Heading in Notebook  
**"Playwright-Based Book Scraper"** (Observation section)

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `books_scraped_1.csv`  
- `books_scraped_1.json`

---

## B. End-to-End Book Scraping & Sentiment-Driven Pricing Pipeline

### Heading in Notebook  
**"End-to-End Book Scraping & Sentiment-Driven Pricing Pipeline"** (Observation section)

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `books_price_adjusted_1.csv`  
- `books_price_adjusted_1.json`  
- `books_scraped_2.csv`  
- `books_scraped_2.json`

---

## C. Interactive News-Driven Book Pricing Pipeline

### Heading in Notebook  
**"Interactive News-Driven Book Pricing Pipeline"**

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `books_price_adjusted_2.csv`  
- `books_price_adjusted_2.json`  
- `books_scraped_3.csv`  
- `books_scraped_3.json`  
- `news_headlines.csv`  
- `news_headlines.json`

---

# 2. Cosine Similarity

## A. Step 1: Web Scraping from the Book

### Heading in Notebook  
**"Step 1: Web Scraping from the book"**

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `books_data.csv`  
- `books_data.json`

### Console Output  
- A separate code block prints sample data in the console.

---

## B. Step 2: News Collection

### Heading in Notebook  
**"Step 2: News Collection"**

### Input  
- User input (entered manually during execution)

### Output Files  
- `news_data.csv`  
- `news_data.json`

### Console Output  
- A separate code block prints sample data in the console.

---

## C. Step 3: Text Cleaning & Cosine Similarity

### Heading in Notebook  
**"Step 3: Text cleaning & cosine similarity"**

### Input Files  
- `books_data.csv`  
- `news_data.csv`  

### Output Files  
- `book_news_similarity.csv`  
- `book_news_similarity.json`

### Console Output  
- A separate code block prints sample data in the console.

---

## D. Step 4: Price Adjustment

### Heading in Notebook  
**"Step 4: Price adjustment"**

### Input Files  
- `books_data.csv`  
- `book_news_similarity.csv`

### Output Files  
- `final_books_pricing.csv`  
- `final_books_pricing.json`

### Console Output  
- A separate code block prints sample data in the console.

---

# 3. Getting Authors, Popularity Index, Reviews

## A. Book Title Scraping – Step 1

### Heading in Notebook  
**"Book Title Scraping Step 1:"**

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `step1_books.csv`  
- `step1_books.json`

### Console Output  
- A separate code block prints sample data in the console.

---

## B. Getting the Book’s Author – Step 2

### PART 1 – Step 2A

#### Heading in Notebook  
**"Getting the books Author Step 2A:"**

#### Input File  
- `step1_books.csv`

#### Output Files  
- `step2_authors_detected.csv`  
- `step2_authors_detected.json`  
- `step2_authors_not_detected.csv`  
- `step2_authors_not_detected.json`

#### Console Output  
- A separate code block prints sample data in the console.

---

### PART 2 – Step 2B

#### Heading in Notebook  
**"Getting the books Author Step 2B:"**

#### Input File  
- `step2_authors_not_detected.csv`

#### Output Files  
- `step2b_authors_not_detected.csv`  
- `step2b_authors_not_detected.json`  
- `step2b_authors_recovered.csv`  
- `step2b_authors_recovered.json`

---

### PART 3 – Step 2C (Merging Authors)

#### Heading in Notebook  
**"Getting the books Author Step 2C Merging the Authors :"**

#### Input Files  
- `step2_authors_detected.csv`  
- `step2b_authors_recovered.csv`  
- `step2b_authors_not_detected.csv`

#### Output Files  
- `final_authors_detected.csv`  
- `final_authors_detected.json`  
- `final_authors_not_detected.csv`  
- `final_authors_not_detected.json`

---

## C. Popularity Index – Step 3

### Heading in Notebook  
**"Getting the popularity index of the authors Step 3:"**

### Input File  
- `final_authors_detected.csv`

### Output Files  
- `author_popularity_index.csv`  
- `author_popularity_index.json`

---

## D. Rating-Based Reviews – Step 4

### Heading in Notebook  
**"Getting the ratting based reviews of Step 4:"**

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `step4_book_ratings.csv`  
- `step4_book_ratings.json`
