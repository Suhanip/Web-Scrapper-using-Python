# Web-Scrapper-using-Python
This repository contains the code file for scrapping price of products from Amazon and fetch it in google spreadsheet and update the date as when the price is fetched.

Steps to be followed:
1. Open the google spreadsheet.
2. Convert the spreadsheet into dataframe.
3. Get the product URL from the dataframe.
4. Checking using soup.find(),which id is present for particular product as for the given data there are 4types of id :     
#priceblock_dealprice, #priceblock_ourprice, #priceblock_saleprice and #mbc-price-1
5. Create two new columns for prices and date modified.
6. Remove other columns having no value('NaN')
