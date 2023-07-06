# challenge-11

Background: This is a web-scrape and data analysis project for Mars data that identifies HTML elements on a page, identifies their id and class attributes, then extracts information via automated browsing with Splinter and HTML parsing with Beautiful Soup.
A repository labeled challenge-12 contains the following files:
*    Code folder
*    part_1_mars_news.ipynb
*    part_2_mars_weather.ipynb
*   Output folder
** avg_press_month.png
** avg_temp_by_month.png
** cold_hot_months_curiosity_location.png
** mars_weather.csv
** terrestrial_days.png

This project consists of two technical products. 

The first product uses file part_1_mars_news.ipynb and Chrome DevTools to scrape titles and preview text from the Mars News website (https://static.bc-edx.com/data/web/mars_news/index.html) through automated browsing. Beautiful Soup object extracts text elements from the website, which is then stored via Python data structure. 
The second product uses file part_2_mars_weather.ipynb and Chrome DevTools to scrape and analyze Mars weather data (https://static.bc-edx.com/data/web/mars_facts/temperature.html) from an existing table. Beautiful Soup object is used to scrape the data in the HTML table, which is then assembled into a Pandas Data Frame.  The data types were examined and converted into the appropriate data types for use in answering questions specific to mars. The plot, bar charts, and csv files are all exported to the output folder. 

Resources used for this project include, Instructor assistance during Office Hours, course material, course provided starter-code, Study Group, GitHub, Stack Overflow, Creative Commons, Towards Data Science, Tutorials Point, Scraper API, and Geeks for Geeks.
