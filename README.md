# Tech Trend Analysis

## Overview

Welcome to the Tech Trend Analysis repository! This project focuses on analyzing technology trends using survey data. The goal is to gain insights into the current landscape of technology usage, preferences, and demographics, which can inform strategic decisions for businesses and organizations.

## Contents

### 1_Data_Collectinon_Using_API.ipynb

This notebook demonstrates how to collect data using an API. The main tasks include:

- Importing required libraries such as `pandas` and `json`.
- Defining a function `get_number_of_jobs_T(technology)` to count the number of job postings for a specific technology by reading data from a JSON file.
- Defining a function `get_number_of_jobs_L(location)` to count the number of job postings for a specific location by reading data from a JSON file.
- Creating a list of locations and writing the number of job postings for each location to an Excel file using `openpyxl`.
- Creating a list of technologies and writing the number of job postings for each technology to an Excel file using `openpyxl`.

### 2_Web_Scraping.ipynb

This notebook focuses on web scraping to collect data on programming languages and their corresponding average annual salaries. The main tasks include:

- Importing necessary libraries such as `BeautifulSoup` and `requests`.
- Fetching HTML content from a URL containing a table of programming languages and salaries.
- Parsing the HTML content to extract language names and their average annual salaries.
- Printing the extracted data in a formatted manner.
- Saving the extracted data to a CSV file named `popular-languages.csv`.

### 3_Survey_Dataset_Exploration.ipynb

This notebook serves as the starting point for our analysis. It explores the survey dataset in detail, performing the following tasks:

- Displaying the first 5 rows of the dataset to understand its structure.
- Determining the number of rows and columns in the dataset.
- Examining the data types of each column to ensure consistency.
- Calculating the mean age of survey participants to understand the age distribution.
- Identifying the number of unique countries represented in the dataset to gauge geographical diversity.

### 4_Data_Wrangling.ipynb

In this notebook, we clean and prepare the dataset for analysis. The data wrangling process involves:

- Identifying and removing duplicate entries to ensure data integrity.
- Handling missing values through imputation techniques to prevent bias in analysis.
- Normalizing the data to bring consistency and standardization, if necessary.

### 5_Exploratory_Data_Analysis.ipynb

The exploratory data analysis (EDA) notebook dives deep into understanding the dataset's characteristics. It includes:

- Exploring the distribution of data across different variables to identify patterns.
- Identifying outliers that may skew the analysis and deciding how to handle them.
- Removing outliers, if necessary, to ensure accurate analysis.
- Examining correlations between variables to understand relationships and potential dependencies.

### 6_Data_Visualization.ipynb

This notebook focuses on visualizing the dataset to extract meaningful insights. It includes:

- Connecting to a database, if applicable, to access additional data sources.
- Creating visualizations such as histograms, box plots, scatter plots, bubble plots, pie charts, stacked charts, line charts, and bar charts.
- Visualizing the distribution of data, relationships between variables, composition of data, and comparisons across different categories.
- Closing the database connection after visualization to ensure data security.

### Tech Trend Analysis.pdf

This document provides a comprehensive overview of the analysis conducted in the previous notebooks. It includes:

- An executive summary summarizing the key findings and implications.
- Discussion of technology trends observed in the data, including JavaScript dominance, PostgreSQL emergence, and demographic insights.
- Methodology overview detailing the approach used for data analysis.
- Results section with visualizations, charts, and a dashboard for easy interpretation.
- Discussion of findings and implications for strategic decision-making.
- Conclusion highlighting the importance of adapting to emerging technologies and addressing demographic challenges.
- Appendix containing additional details, if needed.

## Summary

This analysis provides valuable insights into current technology trends and their potential impact on various industries, aiding in informed decision-making processes.

