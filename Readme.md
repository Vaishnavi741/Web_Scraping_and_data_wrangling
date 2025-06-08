# 📚 Book Web Scraping & Analysis with Python

This project demonstrates how to scrape book data from [Books to Scrape](http://books.toscrape.com/) using `requests` and `BeautifulSoup`, process it using `pandas`, and visualize it with `matplotlib`.

---

## 🔧 Technologies Used

- **Python**
- `requests` for sending HTTP requests
- `BeautifulSoup` for parsing HTML
- `pandas` for data manipulation
- `matplotlib` for data visualization

---

## 📌 Project Features

### 1. Web Scraping

- Fetches data from [books.toscrape.com](http://books.toscrape.com/)
- Extracts:
  - Book Title
  - Price
  - Availability
  - Star Rating

### 2. Data Wrangling with Pandas

- Converts price strings (e.g., `£51.77`) into `float`
- Maps star ratings (`One`, `Two`, ...) to integers (1 to 5)
- Extracts number of items in stock using regex
- Creates a clean `DataFrame` of all books on the homepage

### 3. Data Visualization

- Bar chart of number of books by rating
- Scatter plot of price vs rating

---

## 📈 Sample Visualizations

### ⭐ Number of Books by Rating

> 📊 *Bar chart displaying how many books have 1-star, 2-star, ... 5-star ratings*

![Bar Chart](images/rating_bar_chart.png)

### 💸 Price vs Rating

> 📉 *Scatter plot showing relationship between price and rating*

![Scatter Plot](images/price_vs_rating.png)

---

