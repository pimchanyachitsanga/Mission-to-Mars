# Mission-to-Mars

## Background
The goal of the project is to have information about Mars on a single web page through the use of web scraping, MongoDB, and Flask.

## Software
* Jupyter Notebook
* ChromeDriver
* Splinter and Selenium
* BeautifulSoup
* Python - Pandas
* SQL (NoSQL - MongoDB)
* Flask

## Overview
1. We use Jupyter Notebook file (mission_to_mars.ipynb)to scrape various types of Mars data including recent news from NASA website, Mars facts, and hemisphere image via Splinter, Pandas data frame, and BeautifulSoup
2. We then converted the file to Python (scrape.py) to ensure readable scraper script.
3. We use Flask app used to access this converted Python scraper script and to store the scraped data into a MongoDB database (app.py).
4. HTML file (index.html) displays the data gathered via the Flask app.
5. Final displays can be viewed on the web: http://127.0.0.1:5000/ with a button to scrape the data as frequently as you wish for the most recent update related to Mars.

![webpage]Mission-to-Mars/templates/webpage.png
