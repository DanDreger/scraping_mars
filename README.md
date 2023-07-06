# scraping_mars

Web Scraping project designed to build practice gathering and parsing data from the web

# tech stack
* python
* pandas
* beautiful soup
* splinter
* numpy
* matplotlib

# Urls scraped for this project
* https://static.bc-edx.com/data/web/mars_news/index.html
* https://static.bc-edx.com/data/web/mars_facts/temperature.html

# Assignment

## Deliverable 1: Scrape titles and preview text from Mars news articles.

* Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.
* Create a Beautiful Soup object and use it to extract text elements from the website.
* Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows: Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. An example is the following:
* Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)

## Part 2: Scrape and Analyze Mars Weather Data

* Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
* Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
* Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
* Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

## Part 3 Analyze your dataset by using Pandas functions to answer the following questions:
* How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)?
* Which months have the lowest and the highest atmospheric pressure on Mars?
* About how many terrestrial (Earth) days exist in a Martian year?

Export the DataFrame to a CSV file.

