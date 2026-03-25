##  Why Accuracy is Limited

The model achieves around **55–65% accuracy**, which may seem low compared to typical ML problems. However, this is expected due to the nature of stock market data.

### 📉 Reasons:

- **Market is highly unpredictable**  
  Stock prices are influenced by external factors like news, global events, and investor sentiment, which are not included in the dataset.

- **Short-term prediction is noisy**  
  Predicting next-day or short-term movement is close to random behavior.

- **Limited features**  
  The model uses only historical price-based features and does not include fundamental or macroeconomic data.

- **No future information**  
  The model only learns from past data and cannot foresee sudden market changes.

### ✅ What this means:

- 50% accuracy = random guessing  
- 55–65% accuracy = meaningful pattern learning  

This project focuses on understanding ML pipelines and real-world challenges rather than achieving unrealistic accuracy.
