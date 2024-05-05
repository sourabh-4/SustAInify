
# SustAInify: Energy Price Forecasting and Optimization

## Overview
This project uses LSTM models to predict future energy prices based on historical data of average energy prices (EUR/MWh). It includes data preprocessing, feature engineering, model training, and result visualization.

## Data Description
The dataset contains historical energy price data. The key feature used for predictions is 'Average Prices (EUR/MWh)', which represents the average energy prices over specific time intervals.

## Data Preprocessing
Data preprocessing involves:
1. Loading the data from 'Data.csv'.
2. Handling missing values.
3. Visualizing the energy prices over time to understand trends and patterns.

## Feature Engineering
Features are engineered through:
1. Rolling mean calculations to smooth out short-term fluctuations.
2. Normalization of the data using standard scaling.

## Models
Several LSTM models are trained with varying complexities:
- Model 1: Basic LSTM model.
- Model 2: Enhanced LSTM with additional layers and parameters.
- Model 3: More complex model designed for better performance.

## Training and Evaluation
Models are trained on the processed dataset, and their performance is evaluated based on R-squared values. Predictions are made for the year 2018, and results are visualized to compare the models.

## Optimization
Optimization techniques are applied to select the best model based on cost efficiency and renewable energy usage criteria.

## Usage
To run the project:
1. Ensure all Python dependencies are installed.
2. Execute the cells in the notebook sequentially from data loading to result evaluation.

## Dependencies
- Python 3.8+
- Pandas
- Numpy
- Matplotlib
- PyTorch

## Authors
- Soham Joshi
- Sourabh Kumar Mandal
- Swarup Patil

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
