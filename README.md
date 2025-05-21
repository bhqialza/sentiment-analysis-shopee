# 🛍️ Shopee App Review Sentiment Analysis

## 📱 Project Overview

This project performs sentiment analysis on Shopee mobile app reviews collected from the Google Play Store. The goal is to analyze user feedback and classify reviews as **positive** or **negative** using machine learning techniques, specifically for Indonesian-language text.

## ✨ Key Features

- **Data Collection**
  - Scrapes reviews of the Shopee app using `google_play_scraper`.

- **Text Preprocessing**
  - Cleans and normalizes Indonesian-language text.
  - Handles slang, informal expressions, and stopwords using the `Sastrawi` library.

- **Sentiment Classification**
  - Trained sentiment classification model built using machine learning and deep learning.

## 📦 Requirements

- Python 3.8+
- Required Libraries:
  - `google_play_scraper`
  - `Sastrawi`
  - `pandas`
  - `scikit-learn`
  - `numpy`
  - `tensorflow` (for loading the `.h5` model)

Install all dependencies using:

```bash
pip install -r requirements.txt
