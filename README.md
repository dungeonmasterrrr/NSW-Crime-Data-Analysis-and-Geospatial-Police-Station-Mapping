NSW Crime Analysis and Police Station Mapping


Project Overview

This project analyses crime trends across New South Wales using Python. It cleans and restructures raw crime data, processes police station location data, links suburbs to their nearest police stations, and creates visualisations to identify seasonal and regional crime patterns.

The goal of this project is to turn raw crime and location datasets into clear, actionable insights that could support public safety planning and resource allocation.



Key Features
Cleaned and transformed raw NSW crime data from wide format into long format.
Processed nested police station JSON data into a structured dataframe.
Matched suburbs with nearby police stations using geospatial analysis.
Combined crime records, postcode data, and police station information into a single analytical dataset.
Built summary tables to identify high-incident police stations by crime category.
Visualised seasonal crime patterns in Sydney.
Analysed whether major crimes have decreased overall while certain offences increased in specific areas.


Technologies Used
Python
Jupyter Notebook
pandas
NumPy
GeoPandas
Matplotlib
Seaborn
Project Structure
nsw-crime-analysis/
│
├── nsw\_crime\_analysis.ipynb
├── README.md
└── data/
├── crime\_data.csv
├── police\_stations.json
└── postcodes.json


Main Analysis Steps
Data Cleaning
The crime dataset was repaired, cleaned, reshaped, and converted into a format suitable for time-based analysis. The police station dataset was flattened from nested JSON format and filtered to include relevant NSW stations.
Data Integration
Crime data, postcode data, and police station data were combined. Suburbs were matched with their nearest police stations using geospatial operations.
Summary Analysis
The project created summary tables showing which police stations had the highest number of incidents for each crime category, together with offence rates and trend indicators.
Seasonal Crime Analysis
Sydney crime data was analysed across calendar months to identify seasonal patterns and help the public understand when crime levels tend to be higher.
Recent Crime Trend Evaluation
The project examined whether major crimes have generally declined across NSW while some specific crime categories increased in certain areas.
Key Insights
Theft appeared as one of the most significant crime categories, especially in high-density urban areas.
Some major crime categories showed a general long-term decline.
Certain offences, such as assault, sexual offences, and blackmail/extortion, showed signs of growth in selected areas.
Crime levels in Sydney showed seasonal variation, with some months experiencing higher incident levels than others.
Crime distribution was uneven across NSW, suggesting that resource planning should consider both crime type and location.


How to Run
Clone this repository.
git clone https://github.com/your-username/nsw-crime-analysis.git
Open the project folder.
cd nsw-crime-analysis
Install the required Python libraries.
pip install pandas numpy matplotlib seaborn geopandas
Open the notebook.
jupyter notebook nsw\_crime\_analysis.ipynb
Run the notebook cells in order.
Notes

This project was created for learning and portfolio purposes. The analysis is based on the available datasets and should be interpreted as exploratory data analysis rather than an official crime report.

