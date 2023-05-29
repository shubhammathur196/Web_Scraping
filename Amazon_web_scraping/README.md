
# Web Scraping with Beautiful Soup

This project demonstrates web scraping using Beautiful Soup to extract product information from Amazon.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview
Web scraping is the process of automatically extracting data from websites. This project focuses on scraping product information from Amazon, including the product title, price, rating, reviews, and availability. The Beautiful Soup library is used to parse the HTML content of the webpages and extract the desired information.

## Installation
To run this project, you need to have Python installed on your system. Additionally, you'll need to install the following dependencies:

- Beautiful Soup: `pip install beautifulsoup4`
- Requests: `pip install requests`
- Pandas: `pip install pandas`

Clone this repository to your local machine using the following command:
https://github.com/shubhammathur196/Web_Scraping/Amazon_web_scraping.git



## Usage
1. Open the `main.py` file.
2. Add your user agent to the `headers` dictionary in the main section.
3. Modify the `url` variable to the desired Amazon search page.
4. Run the `main.py` script using the following command:



5. The script will scrape the product information and save it as a CSV file named `web_scraping_results_amazon.csv`.

## Dependencies
- Python 3.x
- Beautiful Soup 4
- Requests
- Pandas

## Contributing
Contributions to this project are welcome. If you find any issues or want to suggest improvements, please open an issue or submit a pull request.

