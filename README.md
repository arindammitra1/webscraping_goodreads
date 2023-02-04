# Webscraping Top 500 book details from goodreads using Python
## With BeautifulSoup and Requests

[Goodreads.com](https://www.goodreads.com) is a comprehensive list of top-rated books, as voted on by the general Goodreads community.

We will use Python, BeautifulSoup and Requests to scrape first 5 pages and create list of top 500 books and some interesting information on them. 

Outline of the Project:
## Part A: 
1. Exploration and scrapping information from 1 page
2. Download a single page from goodread.com and store it
3. Scrape the stored page, and extract the required data from the page with BeautifulSoup

## Part B: Put things together - a Scalable code for any number of pages
1. Create a dictionary to store the book information
2. Write separate functions to scrape a particular information from the BeautifulSoup document, and add it to the dictionary
3. Repeat this for any number of pages by appending new items to the dictionary
4. Store this in a Panda detaframe
5. Save dataframe to a csv file
