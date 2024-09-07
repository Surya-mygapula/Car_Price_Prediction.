# Car_Price_Prediction
## Overview
This project involves a machine learning model for predicting car prices based on various features. The model uses a Random Forest Regressor to estimate the selling price of a car given its attributes.

## Dataset
The dataset used is `car_data.csv`, which contains information about cars, including their selling price. Key features include:

- **Year**: The year the car was manufactured.
- **Mileage**: The mileage of the car in thousands of kilometers.
- **Fuel**: Type of fuel used by the car (e.g., Petrol, Diesel).
- **Transmission**: Type of transmission (e.g., Manual, Automatic).

## Project Structure
- `car_price_prediction.py`: Script for loading data, training the model, making predictions, and saving the model.
- `regressor.pkl`: Saved Random Forest Regressor model.
- `lb.pkl`: Saved LabelEncoder for encoding categorical features.
- `lb1.pkl`: Saved second LabelEncoder for encoding additional categorical features.
