# Chicago_crime_analyser

# Project Overview
This project aims to analyze crime data in Chicago using advanced data science techniques. The goal is to provide valuable insights into crime patterns, trends, and hotspots to aid in decision-making for law enforcement and city planners. The analysis involves data preprocessing, exploratory data analysis (EDA), Geospatial, and the application of various machine learning algorithms.

# Project Structure
* data/: Contains the dataset files
* notebooks/: Jupyter notebooks for data analysis and model development
* src/: Source code for data preprocessing, feature engineering, and model training
* models/: Saved machine learning models

# Usage
# Data Preprocessing
The data preprocessing involves handling missing values, encoding categorical variables, and feature scaling. The script for data preprocessing can be found in src/data_preprocessing.py.

# Exploratory Data Analysis (EDA)
The EDA involves visualizing crime patterns and trends. The EDA notebook can be found in notebooks/eda.ipynb.

# Machine Learning Models
Various machine learning models are trained to predict the type of crime and identify crime hotspots. The scripts for model training can be found in src/models/.
# Key Points:
Imputing Missing Values:
Numerical features are imputed with the mean of the column.
Categorical features are imputed with the most frequent value.
Label Encoding:
Categorical columns are label encoded after imputation.
This should handle the NaNs in your dataset and allow the models to train without crashing.

# Visualization
Geospatial visualizations are created using Folium to map crime incidents and hotspots. The visualization script can be found in src/visualization.py.

# Results
## The results of the analysis include:

* Identification of high-crime areas and times
* Prediction models for crime types
* Interactive maps showing crime hotspots




