Books to Scrape: Web Scraping & Analysis
A Python pipeline built in Google Colab to scrape, clean, analyze, and visualize catalog data from the Books to Scrape website.

Project Structure
* `books_100.csv` — Raw scraped dataset (100 records)
* `books_100_cleaned.csv` — Cleaned dataset with engineered features
* `main_pipeline.ipynb` — Complete Colab notebook (Tasks 1–4)
* `README.md` — Project documentation
  
Overview of Tasks
1. Task 1: Scraping
Uses Scrapy and Crochet to extract title, category, price, rating, stock, UPC, and descriptions across 5 catalog pages.
2. Task 2: Preprocessing & Feature Engineering
Cleans text, converts numeric types, and creates new features .
3. Task 3: Visualization
Generates 5 charts and a Word Cloud of book summaries using Matplotlib and Seaborn.
4. Task 4: Insights & Limitations
Summarizes key findings, answers core business questions, and highlights dataset constraints.

Key Takeaways
1.Price vs. Rating: Price and star ratings are completely independent—higher prices do not mean better ratings.
2.Pricing & Ratings: Prices spread evenly between £10 and £60. Ratings split evenly.
3.Best Value: 4 or 5-star books priced under £25 deliver the highest value score.

Run the code sequentially in Google Colab to extract the data, generate output CSVs, and view interactive plots.
