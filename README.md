# SpaceX Falcon 9 Launch Prediction

This repository contains the complete data science project for predicting the success of Falcon 9 first-stage landings. The project includes data collection, cleaning, analysis, and machine learning model development using various tools and techniques.

## Project Overview

The goal of this project is to predict whether the Falcon 9 first stage will land successfully based on historical data. This involves collecting data from various sources, performing exploratory data analysis (EDA), feature engineering, and building predictive models.

## Repository Structure

The repository includes the following files and notebooks:

### Jupyter Notebooks

1. **`jupyter-labs-spacex-data-collection-api.ipynb`**
   - Collects data from the SpaceX API, cleans it, and saves it in CSV format.

2. **`jupyter-labs-webscraping.ipynb`**
   - Performs web scraping to gather Falcon 9 historical launch records from Wikipedia.

3. **`labs-jupyter-spacex-Data wrangling.ipynb`**
   - Handles data wrangling and normalization of collected data.

4. **`jupyter-labs-eda-sql-coursera_sqllite.ipynb`**
   - Performs exploratory data analysis (EDA) and SQL queries on the dataset.

5. **`DS0203EN_module_2_edadataviz.ipynb`**
   - Contains exploratory data analysis and data visualization tasks.

6. **`DS0203EN_module_3_lab_jupyter_launch_site_location.ipynb`**
   - Analyzes and visualizes launch site locations using geospatial data.

7. **`DS0203EN_module_4_SpaceX_Machine Learning Prediction_Part_5.ipynb`**
   - Implements machine learning models to predict landing success, including model evaluation and hyperparameter tuning.

### Python Scripts

8. **`Dash app.py`**
   - Implements an interactive dashboard using Plotly Dash for real-time visual analytics of SpaceX launch data.

### Datasets

1. **`dataset_part_1.csv`**
   - Contains the first part of the dataset used for analysis and model training.

2. **`dataset_part_2.csv`**
   - Contains the second part of the dataset.

3. **`spacex_web_scraped.csv`**
   - Contains web-scraped data from Wikipedia on Falcon 9 launches.

### Documentation

- **`README.md`**
   - Provides an overview of the project and instructions for use.
