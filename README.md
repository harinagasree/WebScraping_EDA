# WebScraping & EDA

# Web Scraping & Exploratory Data Analysis of the Largest US Companies by Revenue

## Project Overview

This project involves web scraping and exploratory data analysis (EDA) of a Wikipedia page listing the largest companies in the United States by revenue. The goal is to extract, clean, analyze, and visualize the data to uncover meaningful business insights.

Data is programmatically extracted from the publicly available Wikipedia page and includes details like company rank, name, industry, revenue, employee count, and headquarters location. After collection, the data undergoes preprocessing and feature engineering, followed by insightful EDA using visualization libraries in Python.

## Source of Data

Wikipedia Page:
[Largest companies in the United States by revenue – Wikipedia](https://en.wikipedia.org/wiki/List_of_largest_companies_in_the_United_States_by_revenue)

## Data Fields Extracted

The web scraping script extracts the following columns:

* Rank – The company's position in the list based on revenue
* Name – The name of the company
* Industry – The primary sector of operation
* Revenue (USD millions) – The reported annual revenue in USD
* Revenue Growth – The year-over-year growth percentage in revenue
* Employees – Number of employees
* Headquarters – The company's HQ location (city, state)

## Technologies Used

* Python for scripting and data manipulation
* BeautifulSoup & Requests for web scraping
* Pandas for data wrangling and preprocessing
* Matplotlib & Seaborn for visualization

## Exploratory Data Analysis (EDA)

The EDA section provides insights such as:

* Distribution of companies across industries
* Revenue comparison by industry and company
* Correlation between revenue and employee count
* State-wise distribution of company headquarters
* Revenue growth trends and top gainers/losers

Feature engineering steps like splitting the 'Headquarters' column to extract 'City' and 'State', and converting data types appropriately (e.g., revenue to numeric) are also included.

## Goals of the Project

* Automate data extraction from a structured HTML table
* Perform comprehensive data cleaning and transformation
* Generate business insights using visual storytelling
* Provide an end-to-end data pipeline from scraping to analysis

## How to Run

1. Clone this repository
2. Install required packages with `pip install -r requirements.txt`
3. Run `web_scraper.py` to fetch and save data
4. Open `eda_analysis.ipynb` to explore the data insights

This project demonstrates a complete data analysis workflow—starting from real-time data acquisition via web scraping to business insight generation via EDA. It showcases Python's power in automating data collection and creating meaningful, data-driven stories.


