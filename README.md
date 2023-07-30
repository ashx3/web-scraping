# Web Scraping Project

![Web-Scraping-Poster](/images/web_scraping_poster.jpg)

## Context

In this project, we aim to perform web scraping to extract data from various websites and convert it into a workable Python file. Web scraping can be challenging due to the variations in website structures, potential crashes, and limitations on the number of requests allowed by some servers. To overcome these challenges, we will utilize the BeautifulSoup4 library, which provides powerful tools for parsing HTML webpages. By leveraging the functionalities of BeautifulSoup4, we can filter out unnecessary information and extract only the relevant data needed for our analysis.

![Web-Scraping](/images/web_scraping.jpg)


The primary objective is to scrape the list of all Walt Disney Movies from the Wikipedia website. Wikipedia is a vast repository of information, making it an ideal source for our data extraction task. By leveraging web scraping techniques, we will extract the required data from Wikipedia's webpage dedicated to Walt Disney Movies. This data will be valuable for further analysis and insights related to Walt Disney's cinematic productions.<br>

__Target Website: https://en.wikipedia.org/wiki/List_of_Walt_Disney_Pictures_films__

![Wikipedia](/images/wiki_logo.jpg)

## Content

We will utilize the BeautifulSoup and requests Python libraries for web scraping. During the scraping process, we will encounter potential difficulties that can arise when extracting data from websites. Once we successfully scrape the required data from the website, we will also use an API to fetch the scores for the list of movies extracted from the website.<br>

There will be two iPython notebooks in this project:<br>
- __web_scraping_raw.ipynb__ - This notebook will contain all the commands used during the entire project, including messy code with comments to narrate the process. 
- __web_scraping.ipynb__ - This notebook will only include the essential commands, providing a clean and concise view of the code without extensive comments. It will serve as a full-fledged version of the raw notebook.<br>

Additionally, we will have files saved as v1, v2, and v3, representing checkpoints during the project. These files will be saved with different extensions to showcase multiple variants of storing the data.

## How API works

![API](/images/ws/api.jpg)

### Tasks done in this project :
- Web scraping using BeautifulSoup to extract data from websites.
- Cleaning and preprocessing the scraped data.
- Employing regular expressions (re library) for pattern matching and text manipulation.
- Handling and working with dates using the datetime library.
- Saving and loading data using formats such as JSON, pickle, and CSV.
- Accessing and retrieving data from an API using the Requests library.

## FAQs

### __What is web scraping?__
Web scraping is the process of using bots to extract content and data from a website. Unlike screen scraping, which only copies pixels displayed onscreen, web scraping extracts underlying HTML code and, with it, data stored in a database. The scraper can then replicate entire website content elsewhere.

### __Why should we do web scraping?__
That is a good question, web scraping is a integral tool for every business because it allows quick and efficient extraction of data in the form of news from different sources. Such data can then be processed in order to glean insights as required. As a result, it also makes it possible to keep track of the brand and reputation of a company.

### __Is it legal?__
It is perfectly legal if you scrape data from websites for public consumption and use it for analysis. However, it is not legal if you scrape confidential information for profit. For example, scraping private contact information without permission and sell them to a 3rd party for profit is illegal. However you can know your web scraping limits by searching the robots.txt file of the website in google like "amazon robots.txt" and you can find out what you can do and what might get you in trouble!

### __What is BeautifulSoup?__
Beautiful Soup is a Python library that is used for web scraping purposes to pull the data out of HTML files. It creates a parse tree from page source code that can be used to extract data in a hierarchical and more readable manner

### __Which language is best used for web scraping?__
Python is mostly known as the best web scraper language. It's more like an all-rounder and can handle most of the web crawling related processes smoothly. Beautiful Soup is one of the most widely used frameworks based on Python that makes scraping using this language such an easy route to take.

### __What's the difference between web scraping and data mining?__
Web scraping refers to the process of extracting data from web sources and structuring it into a more convenient format whereas data mining refers to the process of analyzing large datasets to uncover trends and valuable insights. It does not involve any data gathering or extraction.
