# web_scraping_challenge
Assignment consist of two technical elements: scrape titles and preview text from Mars news articles; scrape and analyze Mars weather data

Background:

    You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.

    As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

What You're Creating:

    This new assignment consists of two technical products. You will submit the following deliverables:

        Deliverable 1: Scrape titles and preview text from Mars news articles.

        Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

Instructions:

    Part 1: Scrape Titles and Preview Text from Mars News

        Open the Jupyter Notebook in the starter code folder named part_1_mars_news.ipynb.

        Use automated browsing to visit the provided Mars news site. Inspect the page to identify which elements to scrape.

        Create a Beautiful Soup object and use it to extract text elements from the website.

        Extract the titles and preview text of the news articles that you scraped. Store the scraping results in Python data structures as follows:

            Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: title and preview.
            
            Store all the dictionaries in a Python list.

            Print the list in your notebook.

        Optionally, store the scraped data in a file (to ease sharing the data with others). To do so, export the scraped data to a JSON file.

    Part 2: Scrape and Analyze Mars Weather Data

        Open the Jupyter Notebook in the starter code folder named part_2_mars_weather.ipynb. 

        Use automated browsing to visit the provided Mars Temperature Data Site. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.   

        Create a Beautiful Soup object and use it to scrape the data in the HTML table. 

        Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.

        Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.

        Analyze your dataset by using Pandas functions to answer the following questions:
        
            How many months exist on Mars?
            How many Martian (and not Earth) days worth of data exist in the scraped dataset?
            What are the coldest and the warmest months on Mars (at the location of Curiosity)? 
            Which months have the lowest and the highest atmospheric pressure on Mars? 
            About how many terrestrial (Earth) days exist in a Martian year? 

        Export the DataFrame to a CSV file.