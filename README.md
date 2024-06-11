# Bike-Rental-Woolf-MBA
This repository contains a Python notebook for predicting bike demand using multiple linear regression. The project aims to help BoomBikes understand the factors affecting the demand for their shared bikes.

## Project Overview

Bike-sharing systems provide a convenient way for individuals to rent bikes for short-term use. BoomBikes, a bike-sharing service, wants to predict bike demand to optimize their operations and increase revenue, especially after the COVID-19 pandemic.

## Dataset

The dataset includes daily bike demand across the American market based on various factors such as weather conditions, season, and user types. 

### Data Fields

- `season`: Season (spring, summer, fall, winter)
- `yr`: Year (0: 2018, 1: 2019)
- `mnth`: Month (1 to 12)
- `holiday`: Whether the day is a holiday (0: No, 1: Yes)
- `weekday`: Day of the week (0 to 6)
- `workingday`: Whether the day is a working day (0: No, 1: Yes)
- `weathersit`: Weather situation
  - 1: Clear
  - 2: Mist
  - 3: Light Snow
  - 4: Heavy Rain
- `temp`: Temperature in Celsius
- `atemp`: Feeling temperature in Celsius
- `hum`: Humidity
- `windspeed`: Wind speed
- `cnt`: Total rental bikes (target variable)

## Notebook Contents

The notebook performs the following tasks:

1. **Load and Explore Data**: Loads the dataset and displays summary statistics.
2. **Data Cleaning**: Converts numerical labels to categorical and drops unnecessary columns.
3. **Feature Selection**: Selects relevant features for the model.
4. **Data Encoding**: Encodes categorical variables using one-hot encoding.
5. **Model Building**: Builds and trains a multiple linear regression model.
6. **Model Evaluation**: Evaluates the model using R-squared and Mean Squared Error.
7. **Visualization**: Plots actual vs predicted demand.

## License

This project is licensed 
