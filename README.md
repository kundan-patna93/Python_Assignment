# Python_Assignment

Read the csv file that contains all the meta informtion needed for scraping
Iterate through each row in csv and get the ASIN and country code
Build the url dynamically and call it using requests library
Based on the status code execute the condition, if the status code is 404 then the URL is not found else parse the html response using beautiful soup
Extract 4 key information - product price, product image url, product details and product title
Once 100 product information scraped, generate a json file and exit from program with a message
