# Task-Based Notebook: Inputs and Outputs Mapping

This section explains each task in the notebook, the heading to find, the inputs it uses, and the outputs it generates.

---

# 1. Task 1 – Book Data Preparation

## PART 1: Raw Data Extraction

### Heading in Notebook  
**"Extracting UPC code, Book Titles, Prices"**

### Input  
- URL: `https://books.toscrape.com/`

### Output Files  
- `books_raw_data.csv`  
- `books_raw_data.json`

---

## PART 2: SubTask 1 – Clean Book Data

### Heading in Notebook  
**"SubTask 1 of TASK 1 Prepare and store clean book data"**

### Input File  
- `books_raw_data.csv` (generated in Part 1)

### Output Files  
- `task1_subtask1_clean_books.csv`  
- `task1_subtask1_clean_books.json`

---

## PART 3: SubTask 2 – UPC to ISBN Resolution

### Heading in Notebook  
**"Sub-Task 2 of Task 1 UPC to ISBN Resolution Using Hybrid Metadata Sources"**

### Input File  
- `task1_subtask1_clean_books.csv` (generated in Part 2)

### Output Files  
- `task1_subtask2_isbn_found.csv`  
- `task1_subtask2_isbn_found.json`  
- `task1_subtask2_isbn_not_found.csv`  
- `task1_subtask2_isbn_not_found.json`

---

# 2. Task 2 – Competitor Price Collection

### Heading in Notebook  
**"Task 2 Web or API query and find the price of the book in competitor website"**

### Input File  
- `task1_subtask2_isbn_found.csv`

### Output Files  
- `task2_booksrun_competitor_prices.csv`  
- `task2_booksrun_competitor_prices.json`

---

# 3. Task 3 – Price Comparison

### Heading in Notebook  
**"Task 3 compare the price in competitor and our website"**

### Input File  
- `task2_booksrun_competitor_prices.csv`

### Output Files  
- `task3_price_comparison.csv`  
- `task3_price_comparison.json`

---

# 4. Task 4 – Price Adjustment

### Heading in Notebook  
**"Task 4 reduce or increase the prices according to competitor"**

### Input File  
- `task3_price_comparison.csv`

### Output Files  
- `task4_price_adjustments.csv`  
- `task4_price_adjustments.json`
