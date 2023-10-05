![MasterHead](https://cdn.dribbble.com/users/1197989/screenshots/5585685/media/139eef797b4034c31cd8189a717c2022.gif)

# Swiggy Analysis Project
Swiggy Anaysis (bangalore) based on Data Scrapped from website.

---

## Aim of the project 🎯:

The aim of this project is to empower aspiring entrepreneurs in the food industry by leveraging data analysis techniques on Swiggy's extensive dataset. By analyzing Swiggy's data, the project seeks to provide valuable insights and actionable recommendations for individuals looking to start their own restaurant business. This endeavor aims to democratize information, allowing entrepreneurs to make informed decisions, optimize their strategies, and increase their chances of success in the competitive restaurant market.

---

## Project Description 📃:
In this project, we delve into the world of food delivery with Swiggy, one of the leading platforms in the industry. Our project is geared towards extracting valuable insights from Swiggy's vast dataset, employing a multi-faceted approach that combines the power of Python libraries, Excel, and Power Query.

Project Phases:

- Data Extraction using Python Libraries:
  - Utilized Python libraries such as Pandas and Requests to extract raw data from Swiggy's servers.
  - Implemented web scraping techniques to collect real-time data on restaurant listings, customer reviews, and menu items, ensuring a comprehensive dataset for analysis.

- Data Cleaning and Transformation using Power Query:
  - Imported the extracted data into Excel and use Power Query to clean, transform, and structure the dataset.
  - Addressed missing values, standardize formats, and remove duplicates to ensure data accuracy and consistency.
  - Leveraged Power Query's intuitive interface to streamline the cleaning process and prepare the data for in-depth analysis.

- Data Analytics using Excel:
  - Employed advanced Excel functions and statistical analysis tools to derive meaningful insights from the cleaned dataset.
  - Performed descriptive analytics to identify popular cuisines, customer preferences, peak ordering hours, and regional trends.
  - Utilized pivot tables and charts to visualize data patterns, aiding in the identification of key market trends and opportunities.

---

# _Steps involved in process:_

## 1. Web Scrapping ⛏️
Given the dynamic nature of Swiggy's content, a traditional iteration over pages was not possible. Instead, automation was utilized to scroll continuously through the website, retrieving data as it dynamically loaded.By leveraging webdriver and selenium, the automation script was designed to mimic user behavior, scrolling down the Swiggy website to capture the dynamically loaded content. This approach allowed the extraction of data beyond what was initially visible on the screen. As the script scrolled down, it effectively retrieved the data, ensuring a comprehensive dataset for further analysis. Following is he code for website automation:
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/e3f73b58-9e4b-4400-9de5-a5a70ac8b59c)

## 2. Data Cleaning 🧹

In the data cleaning phase, Power Query was utilized to refine the extracted dataset from Swiggy, ensuring its accuracy and consistency for further analysis. Several key cleaning processes were implemented:

1. Cleaning Duplicate Data:
    Duplicate records within the dataset were identified and eliminated using Power Query. Removing duplicates ensured that each entry was unique, preventing any distortions in the analysis due to redundant information.

2. Correcting Location Spelling:
    Inconsistent or misspelled location data was rectified using Power Query transformations. Standardizing the location names not only enhanced the dataset's readability but also facilitated accurate geographical analysis, enabling precise insights into regional trends.

3. Removing Null Values:
    Null or missing values in the dataset were identified and removed to enhance data completeness. Power Query allowed for the easy identification and filtering out of these null values, ensuring that the dataset was comprehensive and reliable for subsequent analysis.

## 3. Insights Generated 📊

1. A detailed examination of restaurant distribution across different areas was conducted. The study focused on prominent areas such as BTM Layout, Indiranagar, and Koramangala, revealing significant insights into the local restaurant landscape.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/0a00b278-9984-4745-8cc8-8ddc9c68fa02)

2. In the analysis of Swiggy data, notably Indiranagar and BTM Layout were offering most expensive dishes, whereas the base the price for all of the areas was the same.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/b1d1726b-6270-4be4-a0fe-eecc5f196053)

3. A focus was placed on determining the popularity of different areas based on the number of ratings received by restaurants. Specifically, restaurants with more than 1000 ratings were considered significant indicators of popularity. Through this analysis, several areas emerged as the most popular hubs for dining experiences.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/687b7052-54ec-48ae-b709-ab811866adc2)

4. A correlation study was conducted to explore the relationship between restaurant ratings and delivery times. Surprisingly, the findings revealed a negative correlation between these two variables. This means that, contrary to common expectations, as delivery times increased, restaurant ratings tended to decrease.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/99433bc8-9029-46ae-a360-a1f586de44c5)

5. A specific focus was placed on identifying areas with the highest number of low-rated restaurants, considering ratings below 3.5 as indicators of low customer satisfaction. This criterion allowed for a detailed examination of areas where diners might face disappointing dining experiences.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/d72b3ac3-100c-4f46-a7b9-1bbef86f0a16)

6. A comprehensive examination was conducted to understand the culinary landscape in different areas. The focus was on identifying the most popular cuisines and their distribution across various regions. Interestingly, the research revealed that a select few cuisines dominated the market, with the top 5-6 cuisines collectively constituting more than half of the total market share.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/0b46d2ae-6122-414f-a1da-73c5c411f541)

7. The Swiggy dashboard offers a user-friendly interface providing insights, highlighting areas with low-rated restaurants, and offering detailed cuisine price information. The addition of the area-wise slicer enhances user interactivity, ensuring a personalized and data-driven decision for entity.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/29bb707e-6924-4d3c-b669-f39eff5cb2f6)

---

# Important Insight
The analysis of low-rated restaurants in specific areas on Swiggy's platform has revealed a compelling investment insight: targeting areas with a high concentration of low-rated cuisines presents a unique business opportunity. In these regions, there is a clear demand for quality food and prompt delivery services. Investors seeking to enter the food industry could strategically focus on these areas, capitalizing on the gap in customer satisfaction. By establishing a restaurant or food delivery service that prioritizes exceptional food quality and timely deliveries, there is a significant potential to capture market share and gain customer loyalty. The existing dissatisfaction among customers in these areas signifies an untapped market eager for improved dining experiences.
![image](https://github.com/Prakash-Khatri/Swiggy_Analysis/assets/133597202/7b2c1337-98e0-4a40-a768-3318dc3bf0a2)

