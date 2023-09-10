# Web Scraping with Python

This Python script demonstrates web scraping using the `requests` and `BeautifulSoup` libraries to extract data from a website. In this example, we scrape historical currency exchange rate data from a specific URL.

## Prerequisites

Before running the script, ensure you have the required libraries installed:

```bash
pip install requests
pip install beautifulsoup4

# Usage
Clone this repository or download the web_scraping.py script.

Modify the url variable in the script with the URL of the website you want to scrape.

Run the script:

```bash
python web_scraping.py

The script will send an HTTP GET request to the specified URL, fetch the HTML content, and parse it using BeautifulSoup.

It will then locate and extract data from a specific table on the webpage. The extracted data includes date, close price, open price, high, low, change, and percentage change.

Finally, the script will print the extracted data for further processing or analysis.
