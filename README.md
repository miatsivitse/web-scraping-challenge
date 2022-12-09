# web-scraping-challenge

**Deliverable 1: Scrape Titles and Preview Text from Mars News**
1. Used automated browsing to open https://redplanetscience.com/. 
2. Created a Beautiful Soup object and use it to extract text elements from the website
3. Extracted the titles and preview text of the news articles. Stored the scraping result pairs in dictionaries 
4. Stored the scraped data in JSON

**Deliverable 2: Scrape and Analyze Mars Weather Data**
1. Used automated browsing to open https://data-class-mars-challenge.s3.amazonaws.com/Mars/index.html. 
2. Created a Beautiful Soup object and used it to scrape the table
3. Assembled the scraped data into a Pandas DataFrame and created list of rows
4. Converted datatypes as needed
5. Analyzed dataset to find:
- How many months exist on Mars?
- How many Martian (and not Earth) days worth of data exist in the scraped dataset?
- What are the coldest and the warmest months on Mars (at the location of Curiosity)? (Plotted the results as a bar chart)
- Which months have the lowest and the highest atmospheric pressure on Mars? (Plotted the results as a bar chart)
- About how many terrestrial (Earth) days exist in a Martian year? (Plotted the results as a line chart)
6. Exported data to .csv
