
# Stock Movement Analysis Based on Social Media Sentiment

This project leverages machine learning and sentiment analysis to predict stock trends based on social media content, specifically tweets. By analyzing the sentiment of tweets, the model identifies potential movements in stock prices, offering an innovative approach to stock trend prediction.

---

## Overview

Stock market trends are often influenced by public sentiment, especially as reflected in social media. This project builds a machine learning pipeline to analyze tweet sentiment and predict stock price movements. Key accomplishments include:

- Achieved 89.8% accuracy in classifying tweet sentiments.
- Demonstrated a 0.6 correlation between tweet sentiments and stock closing prices.
- Utilized multiple supervised learning models to assess and improve prediction reliability.

---
## How it works

The process involves the following steps:
1. **Data Collection**:
    Gathered tweets related to specific stocks using social media scraping techniques.
    Collected corresponding stock price data for analysis.

2. **Data Preprocessing**:
    Cleaned and tokenized tweets to remove noise (e.g., links, special characters).
    Matched sentiment-labeled tweets with relevant stock price movements.

3. **Sentiment Analysis**:

    Used supervised machine learning models such as:
    - Naive Bayes
    - Random Forest
    - Decision Trees
    - AdaBoost
    - Logistic Regression

    Assigned a sentiment score (e.g., positive, neutral, or negative) to each tweet.

4. **Correlation Analysis**:

    Calculated a 0.6 correlation between tweet sentiment and stock closing prices.
    Demonstrated a measurable influence of public sentiment on stock trends.

5. **Stock Trend Prediction**:
    Predicted stock movement based on aggregated sentiment scores.

---
## Results

- **Key Metrics**
    - *Sentiment Analysis Accuracy*: 89.8% in correctly classifying tweets.
    - *Correlation with Stock Prices*: 0.6, indicating a significant link between sentiment and stock trends.
- **Insights**
Positive sentiments generally align with rising stock prices, while negative sentiments correlate with declining prices.
Machine learning models like Random Forest and AdaBoost showed superior performance in sentiment classification.

---
## Features
- Sentiment Classification: Analyzes tweets to classify sentiment as positive, neutral, or negative.
- Stock Trend Prediction: Uses aggregated sentiment data to forecast stock price movement.
- Multi-Model Analysis: Compares results across various machine learning models to ensure robustness.