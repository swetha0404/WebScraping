# Web Scraping Project for Hacksprint Hackathon 2020

Python code to gather information and collect more data from another website based on the first information list. 

This code uses BeautifulSoup, Selenium Webdriver, XLRD, Openpyxl. 

Code flow:
  - Tkinter module used to present a neat User Interface to get the input from the given set of options.  
  - Selenium module web driver is used to automatically traverse through the website and download the list of companies.  
  - BeautifulSoup package to match the company and acquire the URL of the company in ZaubaCorp Database.  
  - Again Selenium webdriver traverses through each company URL to get the Name of Directors of the company.  
  - XLRD module is used to traverse through the company names list in excel file;  storing the URL of companies which are available in the database and then adding the names of directors. 

Other applications of this project:
  - Accessing many websites to collect data and enter forms through webdriving automation (repetitive actions).
  - Retrieve large data more neatly and efficiently through beautiful soup module.
  - Find the duplicates of existing websites.
  - Develop websites based on another website of choice.
