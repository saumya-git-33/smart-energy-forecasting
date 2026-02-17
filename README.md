# Smart Energy Consumption Forecasting ⚡

Deep learning based time-series forecasting system for predicting household power consumption.

## Models Used
- Bidirectional LSTM
- CNN + LSTM Hybrid

## Features
- Hourly resampling
- Feature engineering
- 24-hour future prediction
- Model evaluation metrics (RMSE, MAE, R²)

## How to Run

Install dependencies:
pip install -r requirements.txt

Run project:
python smart_energy_consumption_prediction.py


## Dataset
The dataset used is the UCI Household Power Consumption dataset.
Download it and place inside a folder named `data/` before running the project.

## Output
The model predicts future 24-hour household energy consumption using deep learning time-series forecasting.

