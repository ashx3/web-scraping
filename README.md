# Context

Here, we will scrape data from websites and convert the data into a workable python file. Scraping website data is a tedious task and can create many minor problems because every website is different, it may crash, it may not contain information that you need or too many requests may not possible for certain websites due to server limitations. Many potential problems can occur during a lengthy web scraping session. We shall use BeautifulSoup4 library to scrape and use its functionalities to filter out unnecessary information and extract only the information that we need.

![Web-Scraping](/images/web_scraping.jpg)

In this project, we will scrape the list of all Walt Disney Movies in Wikipedia website.<br
As we all know Wikipedia is the source of every known information, so we shall use it for the same.<br>
__Target Website: https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films__

![Wikipedia](/images/wiki_logo.jpg)

### Project specialization:
- Web scraping with BeautifulSoup
- Cleaning data
- Pattern matching with regular expressions (re library)
- Working with dates (datetime library)
- Saving & loading data with json, pickle & csv
- Accessing data from an API using Requests library

# Content

We shall use BeautifulSoup and requests python library for web scraping. While scraping we shall see the difficulties that we can face while scraping data from websites. After scraping data from the website, we shall also use an API to get the scores for the list of movies that we have extracted from the website.<br
In this project, there will be two ipython notebooks with suffix 'raw' and 'final' 
- __raw__ contains all the commands which were used while doing the whole project, it will be messy but there will be comments to narrate through the whole code  
- __final__ contains only the commands that are necessary which will be an clean experience to view without much comments. It will be an full-fledged version of the raw version
- v1, v2, v3 refers to checkpoints on which the files were saved. Files were saved on different extensions to showcase that the data can be stored in multiple variants as well

# How API works

![API](/images/ws/api.jpg)

# FAQs

__Why should we do web scraping?__<br>
That is a good question, web scraping is a integral tool for every business because it allows quick and efficient extraction of data in the form of news from different sources. Such data can then be processed in order to glean insights as required. As a result, it also makes it possible to keep track of the brand and reputation of a company.

__Is it legal?__<br>
It is perfectly legal if you scrape data from websites for public consumption and use it for analysis. However, it is not legal if you scrape confidential information for profit. For example, scraping private contact information without permission and sell them to a 3rd party for profit is illegal. However you can know your web scraping limits by searching the robots.txt file of the website in google like amazon robots.txt and you can find out what you can do and what might get you in trouble!

__What is BeautifulSoup?__<br>
Beautiful Soup is a Python library that is used for web scraping purposes to pull the data out of HTML and XML files. It creates a parse tree from page source code that can be used to extract data in a hierarchical and more readable manner

__Which language is best for web scraping?__<br>
Python is mostly known as the best web scraper language. It's more like an all-rounder and can handle most of the web crawling related processes smoothly. Beautiful Soup is one of the most widely used frameworks based on Python that makes scraping using this language such an easy route to take.

__What's the difference between web scraping and data mining?__<br>
Web scraping refers to the process of extracting data from web sources and structuring it into a more convenient format whereas data mining refers to the process of analyzing large datasets to uncover trends and valuable insights. It does not involve any data gathering or extraction.
