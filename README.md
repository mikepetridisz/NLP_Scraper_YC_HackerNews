## Datapao
Yet to be finished: Alerting
#### Project Description:
Build a [Hacker News](https://news.ycombinator.com) scraper. Given a BeautifulSoup nested data structure, parse the data and select the following fields: ***Title, URL, Author, Comments, Points, Rank***,  create columns based on these names and save the scraped data in a Spark DataFrame.  Scrape data from user-defined number of stories.  URLs posted by Hacker News users are pointing to different websites - scrape these websites' data, then create an additional column ***Keywords*** and implement Natural Language Procerssing to detect keywords from the text. Implement an execution scheduler that automatically re-runs the program. Create an alerting system, which alerts every time a "keyword" e.g "AI" gets more popular.

**Requirements:**
 - Written in Python 3.5 or 3.6
 - PyCharm IDE
 - Data processing == Apache Spark
 - Cloud (AWS), EC2, S3 

[![Screen-Shot-2019-08-13-at-1-40-30-AM.png](https://i.postimg.cc/d3L30qLW/Screen-Shot-2019-08-13-at-1-40-30-AM.png)](https://postimg.cc/MfJqPJ0R)
