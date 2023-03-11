# IMDb_scraping
Scrapes certain data points of feature films from the IMDb website 

# Movie Data Scraping Project
This project involves web scraping movie data from the IMDb website (www.imdb.com). The data points collected include:
* Movie name
* Year released
* Director name
* Country produced in

# Data Collection
The data was collected using the Python library Selenium. The script navigates to the IMDb website, searches for movies matching a certain criteria (e.g. movies released in a particular year), and then extracts the relevant data points for each movie.

# Data Storage
The final cleaned data was stored in a CSV file for easy analysis and manipulation.

# Usage
To use the script, simply run the scrape_movies.py file and specify the desired search criteria (e.g. movies released in a particular year). The script will then scrape the data and save it to a CSV file.

# Requirements
* Python 3
* selenium
* Time
* CSV
* OS
* requests
* pandas (optional, for storing data in a CSV file)
