# AirBNB-Analysis
# SUMMARY
This project aims to analyze Airbnb data using MongoDB Atlas, perform data cleaning and preparation, develop interactive geospatial visualizations, and create dynamic plots to gain insights into pricing variations, availability patterns, and location-based trends.

# What is AirBNB Data?
Airbnb data is information collected and stored by Airbnb, a popular online marketplace for lodging and vacation rentals.This data includes details about the properties listed on the platform, such as location, amenities, availability, and pricing.It also encompasses user information, such as guest reviews, host profiles. Airbnb uses this data to facilitate bookings, improve user experience, and make informed business decisions.Examples of Airbnb data include information about listings,reviews, host profiles, and pricing.

## What are the attributes of AirBnB Data?
There are many different aspects to AirBnB data from both the consumer and host side of the operation.
### i. Consumer-side data:
This can include user-generated content like reviews and experiences shared in forums.More basic data includes average duration rate.
### ii. Host-side data:
This includes property availabilities, property size and features as well as nightly rates.
# Data dictionary
Data dictionaries are used to provide detailed information about the contents of a dataset or database, such as the names of measured variables, their data types or formats, and text descriptions. A data dictionary provides a concise guide to understanding and using the data.

# Tools and Libraries Used:
1. Python
2. pymongo
3. Pandas
4. Plotly
5. Folium
6. Power Bi
7. Streamlit
## setup & Requirments
```bash
Pip install Pandas
import pandas as pd 
```
```bash
pip install numpy
import numpy as np
```
```bash
pip install matplotlib
import matplotlib.pyplot as plt
```
```bash
pip install seaborb
import seaborb as sns
```
```bash
pip install plotly
import plotly.express as px
```
# Project Approach:
1. **MongoDB Connection and Data Retrieval**: A connection to the MongoDB Atlas database was established and sample Airbnb data was retrieved. 
2. **Data Cleaning and Preparation**: Airbnb dataset was preprocessed by handling missing values, removing duplicates, transforming necessary datatypes and replacing the country codes for choropleth visualizations. 
3. **Geospatial Visualization**: The geospatial data from the Airbnb dataset is used to create interactive folium maps. The distribution of listings across different locations are visualized allowing users to explore prices, ratings, and other relevant factors.
4. **Analysis and Visualization**: Python plotly is used to analyze and visualize how prices vary across different locations, property types, and seasons. 
5. **Dashboard Creation**: Power Bi is used to create a comprehensive dashboard that presents key insights from analysis. 



