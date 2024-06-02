# Airbnb Seattle Data Exploration
This repo contains a Jupyter notebook exploring the Seattle AirBnb dataset.

## Project Motivation
The aim of the project is to analyze the dataset to determine the impact of being a Superhost on bookings, ratings and income, as well as the amenities that impact customer ratings.
The analysis is focused on answering the following questions:
- Are Airbnbs hosted by Superhosts more highly rated?
- Do Airbnbs hosted by Superhosts cost more?
- Do Airbnbs hosted by Superhosts have higher booking rates?
- What is the impact of the number and types of amenities on ratings?

## Getting started
### Configurations and set up
The Jupyter notebook can be downloaded and opened using various platforms. Anaconda is recommended as it is quick and easy to set up. Installation instructions can be found here: https://www.anaconda.com/download.

### Python packages used
- numpy
- pandas
- matplotlib
- seaborn

## Files in the repository
- airbnb_seattle_data_analysis.ipynb: Jupyter notebook containing the project code.

### Data
The details and files for the Airbnb Seattle dataset can be found on Kaggle: https://www.kaggle.com/datasets/airbnb/seattle/data.
The dataset consists of 3 CSV files:
- reviews.csv: contains reviews for listings including the date of the review, the reviewer name and the review text
- calendar.csv: contains the listing availability and price over a year, between 2016-01-04 and 2017-01-02
- listings.csv: contains details about the listing location, booking information, host, amenities and reviews.

## Summary of the results
- Listings hosted by Superhosts do tend to get higher ratings than those hosted by regular hosts.
- Superhosts' Airbnbs also list at higher prices overall, but this varies across some neighbourhoods and property types.
- Superhosts' Airbnbs have similar booking rates to regular hosts' Airbnbs.
- Airbnbs offering more amenities receive higher ratings.
The accompanying blog post summarizing the results can be found on Medium: https://medium.com/@a.louandra/standing-out-in-seattle-4a6318a079b9 

## Acknowledgements
- Kaggle and Airbnb for publishing the Seattle Airbnb Open Data which was used in the analysis. https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata
- Seaborn documentation: https://seaborn.pydata.org/index.html
