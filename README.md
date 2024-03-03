# Stock Price Predictor
  Stock Market Price Prediction with LSTM and Streamlit Web App
## Description
This project aims to develop a machine learning model using Long Short-Term Memory (LSTM) networks and Python to predict stock market price. The project leverages Streamlit to create a user-friendly web application for real-time interaction.

* The effectiveness of this model may vary significantly depending on the chosen stock, economic conditions, and other unforeseen factors.

## Running the Code

To replicate the analysis and run the LSTM model, follow these steps:

1. Install required dependencies: `pip install -r requirements.txt`
2. Execute the Jupyter notebooks in sequential order.

## Model Architecture:

The model utilizes a recurrent neural network (RNN) architecture specifically designed for handling sequential data like stock prices: Long Short-Term Memory (LSTM) networks.

### LSTM Networks:

LSTMs are capable of capturing long-term dependencies within data sequences, making them well-suited for stock price prediction.
They address the vanishing gradient problem that can hinder traditional RNNs in learning long-term relationships.

##Model Training:

* Preprocess the data (data cleaning, normalization, feature engineering).
* Define the LSTM model architecture using TensorFlow Keras.
* Set up hyperparameters.
* Train the model on the prepared data set.
