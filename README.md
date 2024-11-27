
# Real Estate Price Prediction

This repository contains a machine learning project that predicts real estate prices based on various features like house age, proximity to public transport, and neighborhood amenities. The project demonstrates data preprocessing, exploratory data analysis, and building a predictive model for estimating house prices.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Data Description](#data-description)
- [Data Preprocessing](#data-preprocessing)
- [Modeling](#modeling)
- [Setup](#setup)
- [Usage](#usage)
- [Technologies](#technologies)
- [Acknowledgments](#acknowledgments)

## Overview

The objective of this project is to predict house prices per unit area based on real estate features. The insights can assist buyers, sellers, and agents in understanding price determinants and making informed decisions.

## Features

- Analyzes the impact of house age, proximity to MRT stations, and local amenities on house prices.
- Handles real estate data with multiple numerical and categorical features.
- Includes exploratory data analysis (EDA) for data visualization and insight generation.
- Builds a predictive model for house price estimation.

## Data Description

The dataset contains the following columns:
1. **Transaction date**: Date of the real estate transaction.
2. **House age**: Age of the house in years.
3. **Distance to the nearest MRT station**: Distance (in meters) to the nearest Mass Rapid Transit station.
4. **Number of convenience stores**: Count of nearby convenience stores.
5. **Latitude**: Latitude of the property.
6. **Longitude**: Longitude of the property.
7. **House price of unit area**: Price of the house per unit area (dependent variable).

## Data Preprocessing

- Checked for null values (none found in this dataset).
- Explored distributions of key features to understand their relationship with house prices.
- Applied appropriate feature scaling and encoding techniques for model input.

## Modeling

- Built a regression model to predict real estate prices.
- Evaluated the model's performance using metrics like Mean Absolute Error (MAE) and R-squared.

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/username/RealEstatePricePrediction.git
   cd RealEstatePricePrediction
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure the dataset file (`Real_Estate.csv`) is in the project directory.

4. Run the Jupyter Notebook:
   ```bash
   jupyter notebook Real_Estate_Price_prediction.ipynb
   ```

## Usage

- Modify the dataset and parameters to test different scenarios.
- Visualize relationships between features and the target variable using the notebook.
- Extend the project by experimenting with additional machine learning models.

## Technologies

- **Python**: Primary programming language.
- **Libraries**:
  - `pandas`, `numpy` for data manipulation.
  - `matplotlib`, `seaborn` for visualization.
  - `scikit-learn` for machine learning.

## Acknowledgments

- The dataset and problem statement are inspired by real-world real estate challenges and data-driven decision-making needs.


