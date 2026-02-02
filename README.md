# data-analysis-projects
Academic data analysis projects using python and jupyter notebook. 
# Gumtree Property Data Analysis & Clustering

This project analyses property listings from Gumtree Johannesburg to uncover pricing trends, property characteristics, and underlying patterns using data cleaning, exploratory data analysis (EDA), visualisation, and clustering techniques.

## Project Overview
The objective of this project was to collect real-world property data, prepare and clean the dataset, explore relationships between key features, and apply unsupervised learning to identify meaningful clusters within the data.

The project was completed as part of the *Scientific Computing with Python* module in the BSc IT (Data Science) programme.

## Data Collection
- Scraped property listing data from Gumtree using Python
- Extracted listing title, description, location, price, number of bedrooms, and number of bathrooms
- Saved raw data to CSV format for further processing

## Data Cleaning & Preparation
- Removed records with missing critical values (price, location, bedrooms, bathrooms)
- Cleaned price values by removing currency symbols and formatting
- Converted numeric fields to appropriate data types
- Processed and validated the dataset before analysis

## Exploratory Data Analysis (EDA)
Performed exploratory analysis to understand property trends and distributions, including:
- Price distribution by number of bedrooms
- Price by number of bathrooms across locations
- Distribution of properties by location
- Histogram of property prices
- Average property price by location
- Count of properties by number of bedrooms

Each visualisation includes interpretation and observations to support data-driven insights.

## Clustering & Pattern Discovery
- Applied clustering techniques to identify patterns in property data
- Used the Elbow Method to determine the optimal number of clusters
- Clustered properties based on:
  - Price and Location
  - Price and Bedrooms
  - Price and Bathrooms
- Visualised clusters and centroids to interpret grouping behaviour

## Tools & Technologies
- Python
- Pandas
- NumPy
- Matplotlib / Seaborn
- Jupyter Notebook
- Web scraping libraries

## Key Skills Demonstrated
- Data scraping and ingestion
- Data cleaning and validation
- Exploratory data analysis (EDA)
- Data visualisation
- Unsupervised machine learning (clustering)
- Insight communication

## Purpose
This project demonstrates practical, end-to-end data analytics skills, from raw data collection to insight generation, suitable for an entry-level data analyst role.
