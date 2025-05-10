# 📈 Real-Time Stock Sentiment Prediction with Spark Streaming

This project builds a real-time analytics pipeline to predict stock sentiment from Twitter and financial news sources using **Apache Spark Structured Streaming** on **Databricks**. The pipeline consumes tweets and news in real time, applies text preprocessing and NLP-based sentiment scoring, and visualizes trends for stock tickers.

## 🚀 Objective

To analyze incoming text data and generate **real-time sentiment signals** for financial assets (e.g., AAPL, TSLA). The goal is to detect shifts in public sentiment that could influence stock prices or support trading strategies.

## 🔧 Tools & Stack

- Apache Spark Structured Streaming
- Databricks Notebooks
- HuggingFace Transformers (e.g., `finbert`, `distilbert`)
- Twitter API / Simulated Streams
- Python (NLTK, pandas, matplotlib)

## 🧠 Pipeline Overview

1. **Data Ingestion**: Real-time streaming from Twitter and financial APIs
2. **Text Preprocessing**: Tokenization, stopword removal, lemmatization
3. **Sentiment Scoring**: Using transformer-based or rule-based models
4. **Time Window Aggregation**: 10–30 min windows for sentiment tracking
5. **Visualization**: Real-time plots of sentiment trend by stock ticker

## 📊 Key Features

- Custom UDFs for Spark-based sentiment classification
- Watermarking and windowed aggregation
- Real-time visualization dashboard
- Supports cost-efficient deployment in Databricks Community Edition

## 📁 Structure

