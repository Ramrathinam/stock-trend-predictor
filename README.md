#  Stock Trend Predictor

This project predicts stock price movement over the next 5 days using Machine Learning.

## Features
- Real-time stock data using yfinance
- Feature engineering (returns, moving averages, volatility, momentum)
- Random Forest model
- Time-series based prediction

##  Results
Achieved ~55–65% accuracy on historical data

##  Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- yfinance

##  Future Improvements
- Add LSTM (Deep Learning)
- Build web app using Streamlit
##  Why Accuracy is Limited

The model achieves around **55–65% accuracy**, which may seem low compared to typical ML problems. However, this is expected due to the nature of stock market data.

###  Reasons:

- **Market is highly unpredictable**  
  Stock prices are influenced by external factors like news, global events, and investor sentiment, which are not included in the dataset.

- **Short-term prediction is noisy**  
  Predicting next-day or short-term movement is close to random behavior.

- **Limited features**  
  The model uses only historical price-based features and does not include fundamental or macroeconomic data.

- **No future information**  
  The model only learns from past data and cannot foresee sudden market changes.

###  What this means:

- 50% accuracy = random guessing  
- 55–65% accuracy = meaningful pattern learning  

This project focuses on understanding ML pipelines and real-world challenges rather than achieving unrealistic accuracy.
