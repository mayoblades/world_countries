A simple approach to Web-Scraping Tables in Wikipedia pages:
Many people use BeautifulSoup to webscrape, but pandas have a handy  read_html() function  which is a quick and convenient way to turn an HTML table into a pandas DataFrame. 

This function can be useful for quickly incorporating tables from various websites without figuring out how to scrape the site’s HTML. 

However, there can be some challenges in cleaning and formatting the data before analyzing it. But that can be sorted out easily using iloc and loc.

