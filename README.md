# Product-Searching
Using web scraping fetching details from different websites.
Input: It takes a product name or product type(eg:air cooler,mobile,etc) from user.
Output:Results from all the websites are stored in output.csv file (In this we have choosen two websites amazon,flipkart).
Procedure:It uses urlopen class from urlib.request and loads the page specified in the url ,
Using BeautifulSoup we will traverse through html page using html parser 
And we will fetch the results what ever we want using classname
