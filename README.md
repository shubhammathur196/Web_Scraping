# Web Scraping Projects

This repository contains two web scraping projects: Amazon Web Scraping and StepStone Job Posting Scraping.

## Table of Contents
- [Overview](#overview)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Overview
Web scraping is the process of automatically extracting data from websites. These projects demonstrate how to use web scraping techniques to gather specific information from different websites.

### Amazon Web Scraping
The first project focuses on scraping product information from Amazon. It extracts details such as the product title, price, rating, reviews, and availability. The Beautiful Soup library is used to parse the HTML content of the Amazon webpages and extract the desired information.

### StepStone Job Posting Scraping
The second project demonstrates scraping job details from StepStone, a job search website. It collects job titles, company names, locations, and links to the job postings. Beautiful Soup is utilized to parse the HTML structure of the StepStone webpages and retrieve the relevant job information.

## Installation
To run these projects, you need to have Python installed on your system. Additionally, you'll need to install the following dependencies:

- Beautiful Soup: `pip install beautifulsoup4`
- Requests: `pip install requests`
- Pandas: `pip install pandas`

Clone this repository to your local machine using the following command:
https://github.com/shubhammathur196/Web_Scraping.git

## Usage
Each project has its own set of files. Follow the instructions below to use the respective projects:

### Amazon Web Scraping
1. Open the `Web_scraping.ipynb` file in the Amazon Web Scraping project folder in Jupyter notebook.
2. Add your user agent to the `headers` dictionary in the main section.
3. Modify the `url` variable to the desired Amazon search page.
4. Run the `Web_scraping.ipynb` script using the Jupyter notebook.



5. The script will scrape the product information and save it as a CSV file named `web_scraping_results_amazon.csv`.

### StepStone Job Posting Scraping
1. Open the `Data_analyst_jobs_scraping.ipynb` file in the StepStone Job Posting Scraping project folder using Jupter Notebook.
2. Modify the `job_search_keyword` variable to the desired job search keyword.
3. Change the email details and add your password.
4. If you want to use gmail instead of outlook , change the smtb to "smtp.gmail.com" instead of 'smtp.office365.com'
5. Run the `Data_analyst_jobs_scraping.ipynb` script using the Jupyer notebook


4. The script will scrape the job details from StepStone and save them as a CSV file named `job_details.csv`.

## Dependencies
- Python 3.x
- Beautiful Soup 4
- Requests
- Pandas

## Contributing
Contributions to this project are welcome. If you find any issues or want to suggest improvements, please open an issue or submit a pull request.

