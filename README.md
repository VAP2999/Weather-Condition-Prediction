# Weather-Condition-Prediction


This repository contains a machine learning model to predict weather conditions (such as rainy, sunny, snowy) based on various weather attributes. The dataset used for this project includes a combination of historical weather data and station location details.

## Project Overview

The goal of this project is to build a classification model that predicts weather conditions using features such as temperature, precipitation, snowfall, and others. The process includes data cleaning, exploratory data analysis (EDA), feature engineering, and model training. The final model can be used for weather prediction purposes, including helping military movements or assessing geographical patterns.

## Dataset

This project uses two CSV datasets:
- **Summary of Weather Data**: Contains weather-related attributes for each station.
- **Weather Station Locations**: Contains details about the weather stations like location, elevation, and other geographical details.

## Steps in the Project

1. **Data Cleaning and Preprocessing**: 
   - Merging datasets and handling missing values.
   - Removing irrelevant columns and handling outliers.
   - Data transformations like converting columns to appropriate data types.

2. **Exploratory Data Analysis (EDA)**:
   - Identifying patterns and correlations in the dataset.
   - Visualizations like heatmaps, box plots, and bar plots.
   - Trends in temperature data over years and months.

3. **Model Training**:
   - A machine learning model is built using Linear Regression to predict the mean temperature.
   - A classification model can be extended based on weather conditions (sunny, rainy, snowy).
   
4. **Insights & Visualizations**:
   - Analysis of historical weather data, including the hottest and coldest years during WWII.
   - Geographical patterns and the impact of weather conditions on military movements.
   - Investigating heatwaves, coldwaves, and other extreme weather events.

## Getting Started

To run this project locally, follow the steps below:

### Prerequisites

- Python 3.x
- Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn

### Installation

1. Clone this repository:
