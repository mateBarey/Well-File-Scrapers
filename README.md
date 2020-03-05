# Well-File-Scrapers

This Scraper Takes a Well Inventory Excel File with a column of API's and uses Pandas to extract the specific column

containing the unique well identifier API's by turning it from a df to a numpy array. The array is then used to build

a custom string that uses the requests module to download all specific well files from the NMOCD. 

The tools used are:
Selenium
Numpy
Pandas
Requests
