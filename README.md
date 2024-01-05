# IMDB-review-sentiment-analysis
This repository is natural language processing (NLP) project centered on sentiment analysis for IMDb movie reviews. Leveraging recurrent neural networks (RNNs), including LSTM and GRU architectures, the project employs machine learning techniques to classify reviews into positive or negative sentiments.

## Overview
This project focuses on sentiment analysis of IMDb movie reviews using natural language processing (NLP) techniques. The goal is to predict whether a given review expresses positive or negative sentiment. Various recurrent neural network (RNN) architectures, including bidirectional, multilayer, and single-layer models, are explored to achieve the best accuracy. The best-performing model is saved for prediction.

## Dataset
The project utilizes the IMDb movie reviews dataset, a common resource for sentiment analysis tasks. The dataset contains a collection of movie reviews labeled as positive or negative.

## Project Structure
- **`data/`**: Contains the IMDb dataset used for training and testing the sentiment analysis models.
- **`notebooks/`**: Jupyter notebooks for data exploration, model development, and evaluation using various RNN architectures.
- **`models/`**: Saved models after training using different RNN architectures, including the best-performing one.
- **`requirements.txt`**: List of Python packages required for running the project.

## Acknowledgments
The project uses the IMDb dataset, and we're thankful for the availability of this valuable resource.
kaggle data science community, stack overflow

## Results
Review the Jupyter notebooks for detailed results of each neural network architecture. Assessments include accuracy, precision, recall, F1 score, and any other relevant metrics. The performance of each model is thoroughly evaluated to identify strengths and weaknesses.
The following neural network architectures have been explored and evaluated: simple neural network, simple RNN, bidirectional RNN, multilayer RNN, multilayer bidirectional RNN, LSTM, bidirectional LSTM, multilayer LSTM, multilayer bidirectional LSTM, GRU, multilayer GRU, bidirectional GRU, multilayer bidirectional GRU. Each architecture's performance is assessed for accurate sentiment prediction.


Prediction
To make predictions using any of the saved models
