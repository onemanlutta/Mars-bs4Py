# Mars-bs4Py

# Project: Mars Web Scraping and Data Analysis

## Project Overview:

This project focuses on web scraping and data analysis related to Mars. The main objectives are to scrape titles and preview text from Mars news articles and to scrape and analyze Mars weather data using Python, Jupyter Notebook, Beautifal Soup, Pandas, and Splinter (for automated browsing).

## Deliverables:

### Part 1: Scrape Titles and Preview Text from Mars News
- **Jupyter Notebook:** `part_1_mars_news.ipynb`
- **Description:** This notebook contains code that utilizes automated browsing with Splinter and HTML parsing with Beautiful Soup to scrape titles and preview text from Mars news articles. The scraped information is stored in Python data structures and optionally exported to a JSON file.

### Part 2: Scrape and Analyze Mars Weather Data
- **Jupyter Notebook:** `part_2_mars_weather.ipynb`
- **Description:** This notebook contains code that scrapes Mars weather data from a website using Beautiful Soup, assembles it into a Pandas DataFrame, and then analyzes the data to answer specific questions. The analysis includes determining the number of months on Mars, the number of Martian days' worth of data, identifying the coldest and warmest months, finding the months with the lowest and highest atmospheric pressure, and estimating the number of terrestrial days in a Martian year. The final DataFrame is exported to a CSV file.

## File Structure:

Mars-bstPy (repository)  
|  
|-- MarsScraping_Analysis (directory)  
|   |-- part_1_mars_news.ipynb  
|   |-- part_2_mars_weather.ipynb  
|   |-- README.md  
|  
|-- Data_Outputs  
|   |-- mars_news_data.json (optional, if exported)  
|   |-- mars_weather_data.csv  




## Dependencies:
- Python 3.10.14
- Jupyter Notebook
- Beautiful Soup
- Pandas
- Splinter (for automated browsing)

## References:
- Mars News website: [https://mars.nasa.gov/news/](https://mars.nasa.gov/news/)
- Mars Temperature Data Site: [https://static.bc-edx.com/data/web/mars_facts/temperature.html](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

## Source:
The project is part of a web scraping and data analysis challenge. The instructions and specifications were provided as part of a learning curriculum.



## Acknowledgments:
- NASA's Mars News website for providing news articles and data related to Mars.
- edX Boot Camps LLC for operating the Mars News website for educational purposes.
- JPL Image Use Policy for guidelines on using images courtesy of NASA/JPL-Caltech.

## Disclaimer:
The data and analysis presented in this project are for educational purposes only. All data sources and references are duly credited.
