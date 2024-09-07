# Car_Price_Prediction
Car Price Prediction Model
Overview
This project involves predicting car prices based on various features using a machine learning model. The model utilizes a Random Forest Regressor to estimate the selling price of a car from a given dataset.

Dataset
The dataset used in this project is car_data.csv, which contains information about various cars, including features such as:

Year of manufacture
Present price
Fuel type
Seller type
Transmission type
Project Structure
car_data.csv: The dataset file containing car information.
car_price_prediction.py: The main script for preprocessing the data, training the model, and making predictions.
regressor.pkl: Pickled file of the trained Random Forest Regressor model.
lb.pkl: Pickled file of the LabelEncoder for fuel types.
lb1.pkl: Pickled file of the LabelEncoder for transmission types.
Code Explanation
Data Preprocessing: The data is preprocessed by encoding categorical features using LabelEncoder.
Train-Test Split: The dataset is split into training and testing sets.
Model Training: A Random Forest Regressor is trained on the training data.
Prediction: The model is used to predict the selling price of new input data.
Model Saving: The trained model and encoders are saved using pickle for future use.
