# Data-Collection Challenge

## Part 1: Scrape Titles and Preview Text from Mars News
Scraping the Mars News website:
 1. Using automated browsing to visit the Mars news site. Inspecting the page to identify which elements to scrape.
 2. Creating a Beautiful Soup object and using it to extract text elements from the website.
 3. Extracting the titles and previewing text of the news articles that are scraped. Storing the scraping results in Python data structures as follows:
    - Storing each title-and-preview pair in a Python dictionary and, giving each dictionary two keys: title and preview.
    - Storing all the dictionaries in a Python list.
    - Printing the list in your notebook.
4. Storing the scraped data in a file (to ease sharing the data with others) by exporting the scraped data to a JSON file. 

## Part 2: Scrape and Analyze Mars Weather Data
Scraping and analyze Mars weather data.
1. Using automated browsing to visit the Mars Temperature Data. Inspecting the page to identify which elements to scrape.
2. Creating a Beautiful Soup object and using it to scrape the data in the HTML table. 
3. Assembling the scraped data into a Pandas DataFrame. 
4. Examining the data types that are currently associated with each column. 
5. Analyzing your dataset by using Pandas functions to answer the following questions:
    - How many months exist on Mars?
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
         - Find the average minimum daily temperature for all of the months.
         - Plot the results as a bar chart.
    - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
         - Find the average daily atmospheric pressure of all the months.
         - Plot the results as a bar chart.
    - About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
         - Consider how many days elapse on Earth in the time that Mars circles the Sun once.
         - Visually estimate the result by plotting the daily minimum temperature.
    - Export the DataFrame to a CSV file.
