# Decoding Cryptocurrency Sentiments on Twitter using GPT-2

This project aims to analyze public sentiment on cryptocurrency by leveraging a fine-tuned GPT-2 language model to classify tweets into positive, negative, or neutral categories. With the explosive growth of crypto discussions on social media, understanding public mood can provide valuable insights for traders, analysts, and researchers.

Project Overview

The project is divided into three core stages:

1)Data Processing and Preparation
The first stage involves collecting raw Twitter data related to cryptocurrency. The tweets are cleaned by removing noise such as URLs, mentions, hashtags, emojis, and special characters. The text is normalized and labeled based on sentiment, resulting in a clean dataset ready for training. The final processed data is saved in a structured CSV file.

2)Model Training and Saving
The cleaned data is tokenized and used to fine-tune a pre-trained GPT-2 model for sentiment classification. We utilize the Hugging Face Transformers library to streamline training. After training, the model and tokenizer are saved for future use, including deployment in a web app.

3)Web Application Deployment
A simple and interactive Streamlit web application is developed to allow real-time sentiment checking of user-input crypto tweets. The backend loads the saved model and processes inputs to display sentiment predictions instantly.

Features:

Real-time sentiment analysis of tweets

GPT-2 based language model fine-tuned for classification

Clean and modular code structure for reproducibility

Lightweight web interface for user interaction

Tech Stack:

Python, Pandas, Numpy

Hugging Face Transformers, PyTorch

Streamlit (for frontend)

GPT-2 (fine-tuned)
