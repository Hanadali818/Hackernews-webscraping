
#Hacker News Scraper
This Python script scrapes Hacker News for top stories with over 100 votes. It utilizes the requests library for fetching web pages and BeautifulSoup for parsing HTML content.

Usag
Make sure pprint, request, and the BeautifulSoup libraries are downloaded

python scrape.py
View the output containing titles, links, and vote counts of top stories.

How it works
The script sends HTTP requests to Hacker News to retrieve the content of the main page and its second page.
It then extracts relevant information such as titles, links, and vote counts using BeautifulSoup.
Stories with over 100 votes are filtered and displayed in descending order of popularity.
Dependencies
requests: For making HTTP requests
BeautifulSoup: For parsing HTML content

Author
Hanad ALI

License
This project is licensed under the MIT License.
