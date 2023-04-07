# V-mart_store_locator_webscrapping

## steps to extract V-mart stores in india

#### step 1 - Explore the V-mart website and inspect the page of V-mart store locator.  
#### step 2 - Use requests and Beautiful Soup for scraping and parsing data from web. 
#### step 3 - find store name , address , timings , latitude , longitude and contact by their class .

### The most challenging part is to extract coordinates(latitude and longitude) .So to get the coordinates i have used following steps:
### 1 - extracted link of the url present in the class.
### 2 - split the url by '=' because coordinates are written after 'destination =' .
### 3- and at then I took the last value of the url using '[-1]'.

