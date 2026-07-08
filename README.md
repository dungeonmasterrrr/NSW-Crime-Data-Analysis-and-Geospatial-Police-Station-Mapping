# NSW Crime Analysis and Police Station Mapping

## Project Overview

This project analyses crime trends across New South Wales using Python. It cleans and restructures raw crime data, processes police station location data, links suburbs to their nearest police stations, and creates visualisations to identify seasonal and regional crime patterns.

The goal of this project is to turn raw crime and location datasets into clear, actionable insights that could support public safety planning and resource allocation.

## Key Features

- Cleaned and transformed raw NSW crime data from wide format into long format.
- Processed nested police station JSON data into a structured dataframe.
- Matched suburbs with nearby police stations using geospatial analysis.
- Combined crime records, postcode data, and police station information into a single analytical dataset.
- Built summary tables to identify high-incident police stations by crime category.
- Visualised seasonal crime patterns in Sydney.
- Analysed whether major crimes have decreased overall while certain offences increased in specific areas.

## Technologies Used

- Python
- Jupyter Notebook
- pandas
- NumPy
- GeoPandas
- Matplotlib
- Seaborn

## Project Structure

```text
nsw-crime-analysis/
│
├── nsw_crime_analysis.ipynb
├── README.md
└── data/
    ├── crime_data.csv
    ├── police_stations.json
    └── postcodes.json
