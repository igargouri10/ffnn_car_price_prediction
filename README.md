# Feedforward Neural Network for Car Price Prediction

This project implements a feedforward neural network from scratch using NumPy to predict car prices. The model is trained on a dataset of used car listings.

## Features

- Data preprocessing and feature engineering for car data.
- Implemented a neural network with one hidden layer.
- Trained using both batch and stochastic gradient descent.
- Generates and saves various plots for exploratory data analysis.
- Saves the trained model parameters.

## Setup

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/igargouri10/ffnn_car_price_prediction.git
    cd ffnn_car_price_prediction
    ```

2.  **Install dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

3.  **Data:**
    This project requires the `Car Price(in).csv` dataset. Please make sure to place this file in the root directory of the project.

## Usage

Run the main script to perform data processing, training, and prediction:

```bash
python hw4_ismailgargouri.py
```

This will:
- Preprocess the data.
- Generate and save plots in the `plots/` directory.
- Train two models (batch and stochastic GD).
- Save the model parameters to `NNCarPriceParameters_Batch.txt` and `NNCarPriceParameters_Stochastic.txt`.
- Print a sample prediction. 