# Sentiment Analysis using Bi-Directional LSTM
This project is aimed at performing sentiment analysis on a Twitter dataset using bi-directional LSTM. The model architecture classifies the sentiment of a tweet into three categories namely neutral, negative and positive.

## Dataset
The dataset used for this project is a Twitter dataset. It contains a collection of tweets from Twitter users. Each tweet is labeled as either neutral, negative, or positive. The dataset is used to train and test the bi-directional LSTM model for sentiment analysis.

## Model Architecture
The model architecture used in this project is a Bi-Directional LSTM model. The model is implemented using Keras with a TensorFlow backend. The model has the following layers:

    Embedding layer with 40 dimensions
    Bi-Directional LSTM layer with 20 units and 60% dropout rate
    Dense layer with 3 units and softmax activation function

The model is compiled using the RMSprop optimizer and categorical cross-entropy loss function. The accuracy metric is used to evaluate the model.

## Installation

    git clone https://github.com/Sriharsha6902/Sentiment-analysis-using-LSTM.git
    pip install -r requirements.txt
    run
