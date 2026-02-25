# Tehran Housing Price Prediction

This project focuses on predicting real estate prices in Tehran using Machine Learning. The dataset contains approximately 4,000 authentic records of apartment sales.

## Project Overview
The goal is to estimate house prices based on features like **Area, Number of Rooms, Parking, Warehouse, Elevator,** and **Location**.

## Project Structure
* `cleaning.ipynb`: Initial data inspection, handling missing values (Address), and removing outliers (> 250 $m^2$).
* `analysis_modeling.ipynb`: Exploratory Data Analysis (EDA) and building the regression model.
* `housePrice_cleaned.csv`: The refined dataset used for training.

## Requirements
* Python 3.x
* Pandas
* Matplotlib
* Scikit-learn

## Key Findings (Phase 1)
* **Missing Data:** Successfully identified and removed 23 records with missing addresses.
* **Outlier Management:** Filtered properties with an area greater than 250 $m^2$ to focus on the standard residential market.
