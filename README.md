# Rotten Tomatoes Top 100 Movies Scraper

A Python web scraper that collects the top 100 movies of all time from Rotten Tomatoes' editorial list and saves them to a CSV file.

## Features
- Sends HTTP requests with custom headers and checks the response status
- Parses HTML using BeautifulSoup and lxml
- Removes unwanted tags and extracts Tomato Meter, Title and Year
- Exports the cleaned data to CSV

## Tech Stack
Python, Requests, BeautifulSoup, lxml, csv

## Installation
pip install requests beautifulsoup4 lxml

## Usage
1. Clone the repository
2. Open `top_100_movies.ipynb` in Jupyter Notebook
3. Run all cells
4. The output is saved as `top_100_movies.csv`

## Output
| Tomato Meter | Title | Year |
|--------------|-------|------|
| ...          | ...   | ...  |

## Future Improvements
- Analyze the data with Pandas and Matplotlib
- Scrape additional details (genre, director, rating)

## Disclaimer
For educational purposes only. Please respect the website's terms of service.
