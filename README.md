# Screener-Scraper
Multi Purpose Scrapers built for Screener Website

## OVERVIEW

The purpose of the scrapers developed is to extract financial and business-related data from the “SCREENER” platform for each company and organize it in various formats suitable for visualization and analysis. Three distinct scrapers have been created, each employing a unique approach and data storage method. These scrapers are as follows:

 -  1)	Screener_Report: This scraper enables users to manually select individual companies and extract their data from the “SCREENER” platform. The extracted information is consolidated into a comprehensive report stored in an Excel (.xlsx) file. The report is saved in a designated folder called “Screener Reports.”

 -  2)	Screener_One_Excel_DB: Similar to the previous scraper, this tool allows users to manually select individual companies and retrieve their data from “SCREENER.” However, the data is stored in multiple Excel files, categorized based on the type of information, in a single folder named “Screener Individual Data.” This approach facilitates efficient storage in a database system. Each time the scraper is run, the existing files are overwritten, making it specific to the company being searched.

 -  3)	Screener_Appending_Excel_DB: Similar to Screener_One_Excel_DB, this scraper also supports manual selection of companies from “SCREENER” and stores their data in multiple Excel files within a folder named “Screener Append Data.” However, instead of overwriting the existing files, the scraper appends the new company details to the respective Excel files. This allows for simultaneous processing of data and an effective storage solution in a database, as the user can run the scraper multiple times to append data for different companies.

## REQUIREMENTS

The data collection process in the provided scraper for “saverisk.com” requires the following packages and their respective versions:
warnings: Used to suppress warning messages during the execution of the scraper.
- os: Provides functionality for interacting with the operating system, such as creating directories and checking file existence.
- time: Used for introducing delays during the scraping process to ensure proper page loading.
- pandas (version 2.0.0): Used for data manipulation and storage in DataFrames.
- numpy (version 1.23.5): Required for numerical operations and array manipulation.
- requests (version 2.28.2): Enables sending HTTP requests to retrieve web pages’ content.
- xlsxwriter (version 3.1.2): Used for writing data to Excel files.
- beautifulsoup4 (version 4.12.2): A library for web scraping, used for parsing HTML and extracting data from web pages.
- openpyxl (version 3.1.2): Required for working with Excel files in Python.
- msedge-selenium-tools (version 3.141.4): Provides the necessary tools for web scraping using the Microsoft Edge browser.
Make sure to have these packages installed and their respective versions compatible with the scraper code for smooth execution.
####
NOTE: It also requires to download the Microsoft Edge WebDriver executable suitable for your operating system and browser version. The WebDriver allows Selenium to communicate with the Microsoft Edge browser. Make sure to download the appropriate version of the WebDriver and add its location to your system’s PATH variable. This driver must be present in the same directory as where the jupyter notebook is open. The current version utilized in the scraper is: Version: 114.0.1823.79
Stable internet connection is must for the scraper.

KEY NOTE: Initial login to screener from the browser (Microsoft Edge) is must for scraper. Screener requires an account login to display the complete data.
