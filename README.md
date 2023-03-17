# Web-Scraping-Challenge: Mars News and Weather

This challenge is consisted of a full web-scraping and data analysis including two technical products. It involves identifying HTML elements on a page, their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. The two technical tasks are as follows:

    - Deliverable 1: Scrape titles and preview text from Mars news articles.

    - Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


## Deliverable 1: Scrape titles and preview text from Mars news articles:

This task includes scraping the Mars news articles. The steps done are:

    1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.
    2. Create a Beautiful Soup object and use it to extract text elements from the website.
    
    3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
        - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
        - Store all the dictionaries in a Python list.
        - Print the list in Jupyter notebook.
        
    4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)
