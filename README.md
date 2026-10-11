# Premier League Dash Analytics

## Project Overview
This project is a Python-based web scraper and interactive analytics dashboard built for tracking English Premier League statistics. It extracts table data using BeautifulSoup and visualizes key metrics through an interactive Dash web application.

## Data Source
Data is dynamically scraped from the [BBC Sport Premier League Table](https://www.bbc.com/sport/football/premier-league/table).

## Dashboard Features
* **Interactive Filtering:** Filter metrics and charts by selecting specific teams via a dropdown menu.
* **KPI Cards:** Displays Total Teams, Average Points, Total Goals, and Maximum Points.
* **Visualizations:** 
  * Bar chart comparing Team Points.
  * Bar chart comparing Goals Scored by Team.
* **Automated Data Processing:** Scraped data is structured and saved as a CSV file (`premier_league_data.csv`) for the dashboard to render.

## Instructions to Run the Project

### 1. Prerequisites
Ensure you have Python installed. Install the required dependencies using pip:
`pip install requests beautifulsoup4 pandas dash plotly`

### 2. Scrape the Data
Run the scraper script to fetch the latest Premier League data and generate the CSV file:
`python scraper.py`
*(Note: If you are running this from a Jupyter Notebook, simply execute the scraper cell).*

### 3. Launch the Dashboard
Run the Dash application:
`python app.py`
*(Note: If you are using a Jupyter Notebook, execute the dashboard cell).*

Once the server starts, open the provided local URL (typically `http://127.0.0.1:8050/`) in your web browser to view the interactive dashboard.
