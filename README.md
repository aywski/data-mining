# Data Mining Labs (ML Labs)

This repository contains two machine learning laboratory exercises focusing on natural language processing (NLP) sentiment analysis and time series forecasting.

### Lab 1: Sentiment Analysis

##### [Report](lab1/README.md)

This lab focuses on evaluating sentiment classification performance using a pre-trained RoBERTa model. Tasks include:
- Loading and implementing the `cardiffnlp/twitter-roberta-base-sentiment` model
- Processing and analyzing tweets from the MTEB Tweet Sentiment Extraction dataset
- Classifying text into three sentiment categories (negative, neutral, positive)
- Calculating accuracy and F1 scores to evaluate model performance
- Creating and analyzing confusion matrices to identify classification patterns and challenges

### Lab 2: Time Series Forecasting

##### [Report](lab2/README.md)

This lab explores time series prediction techniques using the Air Passengers dataset. Tasks include:
- Preprocessing time series data and creating appropriate train-test splits
- Normalizing data using MinMaxScaler for improved model training
- Engineering lag-based features for time series prediction
- Implementing a linear regression model for numerical forecasting
- Computing error metrics (MAE, MSE) to quantify prediction accuracy
- Visualizing actual vs. predicted values to assess model performance and limitations
