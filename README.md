# Web Scraping Corpus 

This repository contains a small text corpus created by scraping the website books.toscrape.com a site designed specifically for web scraping.
Each row in the corpus corresponds to a single book. The main content is the book description taken from the book’s detail page.

The corpus is stored in the CSV file.

## CSV
The following columns are included in the CSV:

content – Main text for the corpus. This is the book description text. If a description was not available, the book title was used as content.
title; – Title of the book.
category – Category/genre of the book, taken from the breadcrumb navigation.
price – Original price string as shown on the website
availability – Availability information 
rating – Star rating of the book 
url – URL of the book detail page.

## Format of the files

  - CSV file encoded in UTF-8.
    - One row per book.  
 
  - Jupyter Notebook containing all code used for:
    - Downloading the HTML pages.
    - Extracting the book information 
    - Creating the pandas DataFrame.
    - Saving the final corpus as a CSV file.

 ## Terms and conditions 

The data in this repository was scraped from http://books.toscrape.com (http://books.toscrape.com/), which is a publicly available demo website explicitly created for practicing web scraping.
