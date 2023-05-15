# Swiggy_Analysis
Swiggy Anaysis (bangalore) based on Data Scrapped from website.
# Introduction
Data in today's time is a relevent thing, because the more data is aquired the more analysis can be done on it. That is why companies are engaging themselves in collection of data at each step. Such data can be in large amount and is not easily manageable, to manage that data companies requires data scientiests. Such a large amount of data is called "Big Data". And the person who analyse the data are Data Analysts. One of such process can be seen in this project, where we (as a team) share the code for Data Extraction from "www.swiggy.com/" , from it's website wherein I Extracted the data from it's Bangalore Domain, and on the basis of data we did some Exploratory data analysis for valuable insights.
## _Steps involved in process:_
- Data Extraction using Python Libraries
- Data cleaning 
- Data Exploring
- Data Presenting
- Data Analysis

Data extraction from swiggy website can be easily done using pthon libraries like requests and Beautifulsoup like most of the websites, however swiggy uses a dynamic website wherein we it does not uses web page no. for easily iterating over pages for data, instead here we have to scroll down to the end of the page to get more data. So libraries like pyshadow and selenium comes in handy at this part. Using BeautifulSoup, selenium and pyshadow we was able to extract the data into html format, then we used library "html_to_jason" to convert the html data to jason file, which acted as an bridge between python and html format. Then using pandas and numpy libraries we was able to create two data frames one had data for restaurants and other have data for food delivery, then using pandas we dropped any duplicates and checked for null values. lastly we converted it to an excel file format.

After creating an Excel file we imprted both of the file into power querry and performed data cleaning

After data cleaning we studied the data to find the possible insights and clues that might help for a business decision.

we did data visualisation using multiple charts by taking various insights.


