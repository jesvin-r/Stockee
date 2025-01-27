# Stockee

## Overview
The Stockee is a versatile tool developed in Python, 
designed to assist traders in enhancing their trading experiece through doing sentimental analysis on current news.

## Machine Learning Models
 - nlptown/bert-base-multilingual-uncased-sentiment (sentimental analysis)

## Technologies Used
- Python: The programming language used for development.
- Requests: For making API calls.
- Transformers: For model loading and processing.
- Torch: For training the dataset
- Sklearn: For preprocessing
- Keras: For Training the dataset [LSTM, Dropout, Sequential, Dense, Activation]
- Matplotlib: For visualization

## Dataset

The dataset contains several features related to stock price history and news data, such as:

- Stock.csv        : Open, Close, High, Low, Volume
- Headlines.json   : Heading, Date
- daily_scores.json : jsonDate, sentiment scores
- Stock_fin: Combination of data from Stock.csv and Logits from Daily_scores.json

## Model Building and Evaluation
The following algorithms were used to build models:

- BERT: For sentiment analysis on news.
- LSTM: For training time series data

## Key results

- Training RMSE: 34.5291600762991
- Testing RMSE: 44.056295705775376
- Training Accuracy: 97.79%
- Testing Accuracy: 97.53%
- Mean Absolute Error (MAE): 27.646850694444442
- Sharpe Ratio (Actual): 0.04724782814279231
- Sharpe Ratio (Predicted): 0.18995510041713715

## Conclusion
The LSTM provided with an accuracy of 97.8% on the training set and 97.5% on the test set.
The project also highlights the stock price dependent on current news, big events and news relevent to stocks.


