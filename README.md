# House-Price-Prediction

## Introduction
This project demonstrates the use of an Artificial Neural Network (ANN) to predict house prices using the California Housing dataset. The model is trained using TensorFlow and evaluated based on Mean Absolute Error (MAE) and Mean Squared Error (MSE).

## Dataset
The dataset is sourced from the `sklearn.datasets.fetch_california_housing` module. It contains information about different housing parameters such as:
- MedInc: Median Income in block group
- HouseAge: Average house age in block group
- AveRooms: Average number of rooms per household
- AveBedrms: Average number of bedrooms per household
- Population: Block group population
- AveOccup: Average number of household members
- Latitude & Longitude: Geographic location

## Model Architecture
The ANN model consists of:
- Input layer with 128 neurons (ReLU activation)
- Batch Normalization & Dropout (0.1)
- Hidden layers: 64, 32 neurons (ReLU activation)
- Output layer with 1 neuron
- Optimizer: Adam
- Loss Function: Mean Squared Error

## Results
The model's performance is visualized using:
- Loss and MAE curves over training epochs
- Scatter plot of actual vs. predicted prices

## License
This project is open-source under the MIT License.

