# Web-Scraping-Challenge: Mars News and Weather

This challenge is consisted of a full web-scraping and data analysis including two technical products. It involves identifying HTML elements on a page, their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. The two technical tasks are as follows:

    - Deliverable 1: Scrape titles and preview text from Mars news articles.

    - Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.


## Deliverable 1: Scrape titles and preview text from Mars news articles

This task includes scraping the Mars news articles. The steps done are:

    1. Use automated browsing to visit the [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html). Inspect the page to identify which elements to scrape.
    2. Create a Beautiful Soup object and use it to extract text elements from the website.
    
    3. Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:
        - Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview. 
        - Store all the dictionaries in a Python list.
        - Print the list in Jupyter notebook.
        
    4. Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file. (Note: there will be no extra points for completing this.)
    


## Deliverable 2: Scrape and analyze Mars weather data

This part includes scraping and analyzing Mars weather data and follows the steps below:
    
    1. Use automated browsing to visit the [Mars Temperature Data Site](https://static.bc-edx.com/data/web/mars_facts/temperature.html). Inspect the page to identify which elements to scrape.
    
   2. Create a Beautiful Soup object and use it to scrape the data in the HTML table.
   
   3. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website. Here’s an explanation of the column headings:
        - id: the identification number of a single transmission from the Curiosity rover
        - terrestrial_date: the date on Earth
        - sol: the number of elapsed sols (Martian days) since Curiosity landed on Mars
        - ls: the solar longitude
        - month: the Martian month
        - min_temp: the minimum temperature, in Celsius, of a single Martian day (sol)
        - pressure: The atmospheric pressure at Curiosity's location
    
    4. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

    5. Analyze the dataset by using Pandas functions to answer the following questions:
    
### How many months exist on Mars?
           There are 12 months on Mars.

### How many Martian days' worth of data are there?
           There is 1867 Martian days' worth of data in this dataset.

### What is the average low temperature by month?


### What are the coldest and the warmest months on Mars (at the location of Curiosity)?

The following graph shows the average low temperatures by months

![Fig1](https://user-images.githubusercontent.com/120361200/225810509-3caa9f13-9e6b-4d53-aa90-158d57ad14c9.png)


Month 3 is the coldest month and month  8 is the hottest month


### Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:

The following graph plots the average atmospheric pressure by months.

![Fig2](https://user-images.githubusercontent.com/120361200/225810799-067e0cbd-4664-48bb-9140-02da6553f1d3.png)


### How many terrestrial (earth) days are there in a Martian year?

The graph below plots daily minimum temperature against Sol(Martian days). 


![Fig3](https://user-images.githubusercontent.com/120361200/225811137-831805b5-5c96-4ae5-9d88-2677465e54b5.png)


The distance from peak to peak is roughly 1479-796, or 683 days. A year on Mars appears to be about 683 days from the plot. Internet search confirms that a Mars year is equivalent to 687 earth days.
