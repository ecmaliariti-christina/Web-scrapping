# Web Scraping Corpus - Books to Scrape
This repository contains a small text corpus created by scraping data from the website Books to Scrape (https://books.toscrape.com/
), an open-access practice website designed for learning web scraping.

## Description of the Corpus

The dataset includes 20 books, corresponding to all the books displayed on the first page of the website.
For each book, the scraper extracts:

Title, description, category, price, availability, rating, and URL of the book page.

Descriptions were collected directly from the individual book pages. In cases where no description was provided by the website, the value "na" ("not available") was used.
The resulting data is stored in books_corpus.csv and can be used as a miniature text corpus.

## Contribution to research

Although small, this dataset can be used for various introductory research tasks, such as:

Text analysis of book descriptions, identifying themes, computing word frequencies, sentiment analysis, genre or category exploration and basic machine learning exercises. 

## Terms of Use and Scraping Notes

The website Books to Scrape is explicitly created as a training environment for web scraping therefore a robots.txt file is not provided. No additional scraping restrictions are listed.
The site declares itself as a sandbox for scraping practice, therefore scraping the site is permitted for educational purposes.

## Repository Contents

scrape_books.ipynb – Jupyter Notebook with the scraping code
books_corpus.csv – Final cleaned dataset
README.md – Documentation of the project

## Tools Used

Python, BeautifulSoup, Requests, Pandas, Regex
