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

## Key Findings (Phase 2)
* **Correlation Insights:** Identified a strong positive correlation between `Area` and `Price`. Features like `Parking` and `Elevator` also showed a significant impact on the final valuation.
* **Geographical Trends:** Observed substantial price variations across different Tehran districts, confirming that `Address` is one of the most influential predictors.
* **Model Performance:** Implemented a Linear Regression model to predict house prices. The model's performance was evaluated using metrics such as R-squared and Mean Absolute Error (MAE) to ensure reliability.

## Conclusion
This project demonstrates the full data science pipeline—from raw data cleaning to deploying a predictive model. The results provide a data-driven perspective on the Tehran real estate market, highlighting the key factors that drive property values.
