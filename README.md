# BeautifulSoup--challenge

# Overview

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organizing and storing data, analyzing data, and then visually communicating your insights.

# Part 1: Scrape Titles and Preview Text from Mars News

- Opening the Jupyter Notebook named part_1_mars_news.ipynb in the starter code folder.
- Using automated browsing to visit the Mars news site. Inspect the page to identify which elements to scrape.
- Creating a Beautiful Soup object and use it to extract text elements from the website.
- Extracting the titles and preview text of the news articles. Store each title-and-preview pair in a Python dictionary with keys title and preview.
- Storing all dictionaries in a Python list and print the list in your notebook.
- Optionally, exporting the scraped data to a JSON file for ease of sharing.

# Part 2: Scrape and Analyze Mars Weather Data

- Opening the Jupyter Notebook named part_2_mars_weather.ipynb in the starter code folder.
- Visiting the Mars Temperature Data Site using automated browsing. Inspect the page to identify elements to scrape.
- Using Beautiful Soup to scrape data in the HTML table.
- Assembling the scraped data into a Pandas DataFrame with columns matching the website's table headings.
- Examining and adjust the data types for each column as necessary.
- Analyzing the dataset to answer questions about Martian months, days, temperatures, and atmospheric pressure. Include bar chart visualizations.
- Exporting the DataFrame to a CSV file.
