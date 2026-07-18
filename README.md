# Zomato Analysis Project
This project performs Exploratory Data Analysis (EDA) on a Zomato dataset, focusing on data cleaning, processing, and visualization. The aim is to derive meaningful insights about restaurant ratings, locations, cuisines, and more.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Dataset](#dataset)
3. [Data Cleaning](#data-cleaning)
4. [Exploratory Data Analysis](#exploratory-data-analysis)
5. [SQL Analysis](#sql-analysis)
6. [Conclusion](#conclusion)

# Project Overview
This project demonstrates:

- **Data Cleaning**: Handling missing values, duplicate records, and normalizing columns.
- **Data Processing**: Cleaning specific columns like ratings, restaurant types, and costs.
- **Visualization**: Using Excel dashboards to visualize relationships and distributions across various restaurant features.
- **SQL Analysis**: Extracting key business metrics through complex queries.

## Dataset
The dataset used in this project is Zomato restaurant data, which contains information like restaurant names, locations, cuisines, ratings, and more.

**Columns used**:

- Restaurant name
- Location
- Online order availability
- Booking table facility
- Ratings, Votes
- Cuisines, etc.

## Data Cleaning
Data cleaning steps include:

 - Handling missing values in the data.
 - Standardizing column formats (Currency, Date keys) for better analysis.
 - Establishing relationships between the main data and reference tables (Country and Currency codes) using Power Pivot.

## Exploratory Data Analysis
We start by understanding the dataset with:

  - Checking dataset shape and columns.
  - Building an interactive dashboard to visualize trends in restaurant performance.
  - Analyzing service availability (Online Delivery vs Table Booking).

## SQL Analysis
We utilized SQL for deep-dive analysis of the dataset:
- Performed aggregations to find city-wise restaurant distribution.
- Calculated performance metrics like average ratings per price tier.
- Analyzed service availability using complex filtering techniques.
*(Refer to `queries.sql` in this repository for the complete script.)*

## Conclusion
This project provided insights into various features of restaurants in the dataset. By cleaning and visualizing the data, we observed patterns related to restaurant ratings, the availability of online orders, and location-specific trends. These insights could help in making informed decisions about dining preferences.

