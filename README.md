# Stock Price Prediction using LSTM

This project demonstrates the use of Long Short-Term Memory (LSTM) networks for predicting stock prices. The model is built using historical stock price data and is implemented using Python, Keras, and various data processing libraries.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Requirements](#requirements)
- [Installation](#installation)
- [License](#license)

## Project Overview
This project aims to predict future stock prices based on historical data. It uses an LSTM neural network, which is well-suited for time series forecasting tasks due to its ability to remember long-term dependencies.

## Data Source
The stock price data is sourced from Stooq and covers the period from January 2012 to December 2023.


## Requirements
- Python 3.7+
- Libraries: 
  - pandas
  - numpy
  - matplotlib
  - scikit-learn
  - keras
  - pandas_datareader

## Installation
- Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name

- pip install -r requirements.txt

- jupyter notebook notebooks/stock_prediction.ipynb


## License

### Instructions for Completing the Project

1. **Download the stock data**:
   - Use the `pandas_datareader` library to download stock data from Yahoo Finance.

2. **Preprocess the data**:
   - Scale the data using `MinMaxScaler`.
   - Split the data into training and testing sets.

3. **Create the LSTM model**:
   - Use the Keras library to build and compile the LSTM model.
   - Train the model using the training data.

4. **Make predictions**:
   - Use the model to predict stock prices on the test data.
   - Inverse transform the scaled predictions to get actual values.

5. **Visualize the results**:
   - Plot the actual vs. predicted stock prices using Matplotlib.

6. **Save the model and results**:
   - Save the trained model to the `models` directory.
   - Save the prediction plot to the `results` directory.

By following this README and completing the project steps, you'll have a comprehensive stock prediction project that you can showcase on your GitHub profile.
