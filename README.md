# python
A body of code for useful snippets and functions of python code blocks from scrapers to ssl, database from past working examples

Top level Python code organized and ranging from scraping, database, API connection files for reference purposes. The old school way of storing our code blocks. 
Some items are general scripts to apply to various urls and parse using Beautiful soup.

# Feeding Package
instagram scraper - need to find the api may be a meta api now. 

# PythonScrape - Master
This package was achieved from code 5 years ago. Its intent was to capture information for curiosity sake and to dabble with python.
It is a generalized bucket of code and `output.txt` Its initial intent in a github repo is to access code bases for a variety of needs but mostly exploring a crawler, its techniques and migrations into a database. See the `#Secondary-folder` section below for further explanations of the code in subdirectories. 
research.py

## License Spring API:
  A compilation of python connectors to read data for database consumption (license_spring folder) This body of code reflects the process of bring an external crm data and a licensing data together to merge the information. It was utilized in an ETL into Hubspot CRM.


## Mysql-code:
Database level code for injesting data from csvs and api json data. Used as a basic block of work for ETL purposes to ingest data.



## General scripts:
Screen Scraper for various industry, amazon best sellers, beauty products recipe scrapper and stock scraper
 

## Utilities Top Level
Reading folder files to injest in database
Outputing excel from database


## To Begin Navigating the top level repository

--

### Topic -- Stocks
bestPerformers.py
biotechstocks.py
stockScrape.py, stockBestPerformers.py, 
htmlReaderBloomberg.py
file reads stocks from a dividend stock website, another for bloomberg and writes to files. 
Parsing of the web component xpath to strip the components interested in.

--

### Topic -- Beauty
crawlProducts.py
Lush -- dailyBestSellersLush.py, lushBestSellersAll.py, LushFace.py,LushFaceTest.py, LushHairShampoo.py, lushIngredients.py,lushLeavingSoon.py
Humblebee.py
JustNaturals.py JustNaturalsURLs.py
AnniesRemedies.py
etsyBath.py
Amazon- beauty best sellers, htmlReaderAmazon.py, htmlAmazonSkinCareReader.py
detox_market.py

### Topic -- Psychology
psychArticles.py
happinessLinks.py


### HTTP/SSL/Server/Database feature code to connect through the servers 
databaseConnectionFromStackO.py
requestSample.py

### Utilities
OutboundAPICAL.py
convertPyFiletoApp.py -- to make into an app to run on scheduler to scrape Amazon Best Sellers for Beauty (MACOS)
scheduledRun.py
htmlCrawler.py
htmlCrawlerTest.py
randomExamples.py
randomNamesGenerator.py
readFolder.py
stringRelace.py
UserAgentList.py used to obfuscate the browser user agent as a friendly hacking experiment against Amazon web scraping


### Schedule Run Service
sheduledRun.py

### Models - Contact
create-contact.py
scrapeModule.py
dealsSample.py - API connection to Hubspot using python




