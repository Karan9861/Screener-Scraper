# Screener-Scraper
Multi Purpose Scrapers built for Screener Website

OVERVIEW
- The purpose of the scrapers developed is to extract financial and business-related data from the “SCREENER” platform for each company and organize it in various formats suitable for visualization and analysis. Three distinct scrapers have been created, each employing a unique approach and data storage method. These scrapers are as follows:

1)	Screener_Report: This scraper enables users to manually select individual companies and extract their data from the “SCREENER” platform. The extracted information is consolidated into a comprehensive report stored in an Excel (.xlsx) file. The report is saved in a designated folder called “Screener Reports.”

2)	Screener_One_Excel_DB: Similar to the previous scraper, this tool allows users to manually select individual companies and retrieve their data from “SCREENER.” However, the data is stored in multiple Excel files, categorized based on the type of information, in a single folder named “Screener Individual Data.” This approach facilitates efficient storage in a database system. Each time the scraper is run, the existing files are overwritten, making it specific to the company being searched.

3)	Screener_Appending_Excel_DB: Similar to Screener_One_Excel_DB, this scraper also supports manual selection of companies from “SCREENER” and stores their data in multiple Excel files within a folder named “Screener Append Data.” However, instead of overwriting the existing files, the scraper appends the new company details to the respective Excel files. This allows for simultaneous processing of data and an effective storage solution in a database, as the user can run the scraper multiple times to append data for different companies.
