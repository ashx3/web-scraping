## Context

Here, we will scrape data from websites and convert the data into a workable python data. Scraping website data is a tedious task and can create many minor problems because every website is different, it may crash, it may not contain information that you need or too many requests may not possible for certain websites. Many potential problems can occur during a lenthty web scraping session.

In this project, we will scrape particular data i.e. list of Walt Disney Movies in Wikipedia website. As we all know Wikipedia is the source of every known information so we shall use it for the same.
Target Website: https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films

We shall use BeautifulSoup and requests python library for web scraping. While scraping we shall see the difficulties that we can face while scraping data from websites. 
After scraping data from the website, we shall also use an API to get the scores for the list of movies that we have extracted from the website.

Project specialization:
- Web scraping with BeautifulSoup
- Cleaning data
- Pattern matching with regular expressions (re library)
- Working with dates (datetime library)
- Saving & loading data with json, pickle & csv
- Accessing data from an API using Requests library

# Content

In this project, there will be two ipython notebooks with suffix 'raw' and 'final' 
- __raw__ contains all the commands which were used while doing the whole project, it will be messy but there will be comments to narrate through the whole code  
- __final__ contains only the commands that are necessary which will be an clean experience to view without much comments. It will be an full_fledged version of the raw version


# FAQ's

Why should we do web scraping?
That is a good question, web scraping is a integral tool for every business because it allows quick and efficient extraction of data in the form of news from different sources. Such data can then be processed in order to glean insights as required. As a result, it also makes it possible to keep track of the brand and reputation of a company.

Is it legal?
It is perfectly legal if you scrape data from websites for public consumption and use it for analysis. However, it is not legal if you scrape confidential information for profit. For example, scraping private contact information without permission and sell them to a 3rd party for profit is illegal. However you can know your web scraping limits by searching the robots.txt file of the website in google like amazon robots.txt and you can find out what you can do and what might get you in trouble!

What is BeautifulSoup?
Beautiful Soup is a Python library that is used for web scraping purposes to pull the data out of HTML and XML files. It creates a parse tree from page source code that can be used to extract data in a hierarchical and more readable manner

Which language is best for web scraping?
Python is mostly known as the best web scraper language. It's more like an all-rounder and can handle most of the web crawling related processes smoothly. Beautiful Soup is one of the most widely used frameworks based on Python that makes scraping using this language such an easy route to take.

What's the different between web scraping and data mining?
Web scraping refers to the process of extracting data from web sources and structuring it into a more convenient format whereas data mining refers to the process of analyzing large datasets to uncover trends and valuable insights. It does not involve any data gathering or extraction.