California Housing Data Analysis

Analyze, visualize, and prepare the California housing dataset for machine learning regression tasks using Python.

Project Overview
This notebook demonstrates the end-to-end workflow for exploring and engineering features from the California Housing dataset. It covers data download, exploration, visualization, train/test splits, and feature engineering for later modeling.

Installation
Clone the repository or download the notebook. Ensure Python (3.8+) and the following libraries are installed:

pip install numpy pandas matplotlib scikit-learn

Modify the dataset download path in the code if needed. Default is D:/datasets/housing.

Data Sources
Data: Hands-On Machine Learning repository (https://github.com/ageron/handson-ml)
Dataset includes longitude, latitude, housing_median_age, total_rooms, total_bedrooms, population, households, median_income, median_house_value, and ocean_proximity.

Code Structure
- Data download: Downloads and extracts housing dataset to local directory.
- Loading: Loads CSV data into pandas DataFrame.
- Exploration: Uses head(), info(), describe(), and value counts for basic analysis.
- Visualization: Plots histograms, scatter plots for geographic patterns, and feature relationships.
- Train/Test Split: Demonstrates multiple split strategies, including stratified sampling by engineered income categories.
- Feature Engineering: Adds rooms_per_household, bedrooms_per_room, and population_per_household.

Results
Visualizations show feature distributions, geographical clustering, and correlations (such as income vs. house value).
Feature engineering prepares the dataset for regression and machine learning modeling.

References
Dataset: Hands-On Machine Learning with SCikit_learn book
Libraries: pandas, numpy, matplotlib, scikit-learn

