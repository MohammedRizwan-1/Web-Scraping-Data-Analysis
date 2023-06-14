# Web-Scraping-Data-Analysis
The purpose of this project is to extract information from Mars News website and Mars Temperature Data website via both automated browsing with Splinter and HTML parsing with Beautiful Soup. Information stored in HTML tables and recurring elements such as multiple news articles on a webpage are extracted. The requirement is to scrape, organize, analyze, and visualize the data.

The deliverables of this project are:

Scrape titles and preview text from Mars news articles and export the data into a JSON file
Scrape and analyze Mars weather data, which exists in a table
This document explains the steps taken to produce the deliverables. They are:

* Collecting data
* Organizing and storing data
* Analyzing data
* Visually communicating the insights

## Summary
The analysis provides the following insights:
* Mars has 12 months
* There are 1867 Martian days' worth of data exist in the Mars Weather dataset
* Month 2 & 3 are the coldest months at -83 Celsius and month 7 is the warmest month at -68 Celsius in Mars.
* Month 6 has the lowest atmospheric pressure at 745.054422 and moth 9 has the highest atmospheric pressure at 913.30597
* There are 686 terrestrial days exist in a Martian year (calculated using solar longitude data in the scraped dataset)
* Below chart supports that calculation as there are clearly 3 temperature cycles in 2,000 days

## Comments and Thoughts
I learned a lot from this challenge. My biggest struggle was getting my table into a dataframe using a loop. It was super easy to just use the pd.read.html, but I struggled to get my loop right with some perseverance and researching I managed to get it working correctly in the end.