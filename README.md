# Web Scraping and Data Analysis of Mars

## The martians need some help with data analysis!

![image](https://github.com/meehal0203/Module_11_web_scraping/assets/146681542/08f3710b-249a-4855-b0bc-82c080448be1)

This assignment consists of two technical products. I will submit the following deliverables:

Deliverable 1: Scrape titles and preview text from Mars news articles.

Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

## Part 1.
### Use automated browsing to visit the Mars news siteLinks to an external site.. Inspect the page to identify which elements to scrape.


* Create a Beautiful Soup object and use it to extract text elements from the website.

* Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

* Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview

* Store all the dictionaries in a Python list.

* Print the list in your notebook.

* Store the scraped data in a file to ease sharing the data with others, exporting the scraped data to a JSON file.

* ## Part 2.
### Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape.

* Create a Beautiful Soup object and use it to scrape the data in the HTML table.

* Assemble the scraped data into a Pandas DataFrame.

* Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

* Analyze your dataset by using Pandas functions to answer the following questions:

How many months exist on Mars?
How many Martian (and not Earth) days worth of data exist in the scraped dataset?
What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
Find the average minimum daily temperature for all of the months.
Plot the results as a bar chart.

* Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average daily atmospheric pressure of all the months.
Plot the results as a bar chart.

* About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.

* Export the DataFrame to a CSV file.

