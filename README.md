# Web_Scraping_Challenge
Module 11 Challenge
In this project, I completed a web-scraping and data analysis challenge that involved extracting information from various Mars-related websites. The project consisted of two main parts: scraping titles and preview text from Mars news articles and scraping and analyzing Mars weather data from an HTML table.

For the first part, I used automated browsing with Splinter and HTML parsing with BeautifulSoup to visit the Mars news site and extract the titles and preview text of the news articles. I stored the scraped data in Python dictionaries and added them to a list, which I printed in the Jupyter Notebook. Optionally, I also exported the data to a JSON file for sharing purposes.

In the second part, I again used automated browsing and BeautifulSoup to visit the Mars Temperature Data Site, which had the weather data presented in an HTML table. I used Pandas and BeautifulSoup to scrape and assemble the data into a DataFrame with appropriate columns and data types. I then performed data analysis using Pandas to answer specific questions, such as the number of months on Mars, the number of Martian days worth of data in the dataset, and the coldest and warmest months on Mars. I visualized the results using bar charts to gain insights into the weather patterns on Mars.

There are approximately 12 months on Mars, and we have 1,867 Martian days worth of data available. 

![98af8f1f-6ce0-4188-9e89-3795d918093e](https://github.com/aliciahlavac/Web_Scraping_Challenge/assets/127240852/5d7b487d-529e-43a8-979b-300c020a303f)

In addition, it was found that the third month, on average, had the coldest average minimum daily temperature while the eighth month had the highest.  

![39b2a0ac-f411-493d-be6a-a5d94e79b107](https://github.com/aliciahlavac/Web_Scraping_Challenge/assets/127240852/5d15c994-3d55-43a3-9141-16875d45b319)

It was also found that the sixth month had the lowest average atmospheric pressure, while the ninth month had the highest.

![b2db7ebe-a51e-42b4-9e22-801de6eed598](https://github.com/aliciahlavac/Web_Scraping_Challenge/assets/127240852/ae0fe39b-77e9-4ca2-a84f-adbcbe9202c7)

Lastly, we found that a year on Mars is about 680 days, by looking at the difference between the two troughs.  

Throughout the project, I practiced my web-scraping skills, identifying relevant HTML elements, extracting data, and handling exceptions when necessary. Additionally, I demonstrated proficiency in using Python libraries such as Pandas and Matplotlib for data manipulation and visualization.

The final deliverables of this project include the Jupyter Notebooks for both parts, containing the code and results of the web scraping and data analysis. The data extracted from the Mars news articles and Mars weather table can be found in the respective parts of the notebooks [part_1_mars_news.ipynb](https://github.com/aliciahlavac/Web_Scraping_Challenge/blob/main/part_1_mars_news.ipynb) and [part_2_mars_weather.ipynb](https://github.com/aliciahlavac/Web_Scraping_Challenge/blob/main/part_2_mars_weather.ipynb). The project not only showcases my web-scraping abilities but also demonstrates my data analysis and visualization skills, making it a valuable addition to my portfolio.
