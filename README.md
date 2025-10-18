# Social-Media-Analytics-
# Project Description

This project focuses on analyzing customer opinions and experiences about Starbucks by extracting posts from Reddit using the PRAW (Python Reddit API Wrapper).
The goal is to understand public sentiment, identify common discussion topics, and derive actionable insights to improve brand experience and customer satisfaction.

# Objectives

- Collect real Reddit data from the r/Starbucks subreddit.

- Clean and preprocess text data for analysis.

- Perform sentiment analysis using VADER from NLTK.

- Visualize sentiment distribution across Reddit discussions.

- Identify frequently used positive and negative keywords to uncover customer opinions and pain points.

# Tools & Libraries

- Python

- PRAW – for Reddit API connection and data collection

- Pandas – for data manipulation

- NLTK – for text preprocessing and sentiment analysis

- Matplotlib – for visualization

- Regular Expressions (re) – for cleaning raw text data

# Data Pipeline Overview

1- Data Collection:

- Connected to Reddit API using PRAW.

- Extracted top 50 “Hot” posts from the r/Starbucks subreddit.

- Stored data (content, username, post date) into a CSV file: starbucks_posts.csv.

2- Text Preprocessing:

- Removed URLs, special characters, and numbers.

- Converted text to lowercase.

- Tokenized text, removed stopwords, and applied lemmatization.

- Saved cleaned data in preprocessed_starbucks_data.csv.

3-Sentiment Analysis:

- Used VADER sentiment analyzer to classify posts into:

  - Positive 😊

  - Negative 😞

  - Neutral 😐

- Stored results in starbucks_sentiment.csv.

4- Visualization:

- Created Pie Chart and Bar Chart showing sentiment distribution.

- Identified top positive and negative keywords using word frequency counts.

# Key Insights

- Majority of posts about Starbucks are positive, showing strong brand loyalty.

- Common positive keywords: “coffee”, “love”, “flavor”, “drink”, “store”.

- Common negative keywords: “wait”, “late”, “service”, “dirty”, “expensive”.

- Customer sentiment highlights appreciation for Starbucks drinks and ambiance, but also mentions issues like long waiting times and inconsistent service.

# 💡 Recommendations

- Enhance Customer and Employee Experience:

- Train staff to improve communication, accuracy in orders, and faster problem resolution.

- Leverage Strengths and Address Gaps:

Build on customer appreciation for taste and ambiance by launching new seasonal beverages.

Improve operational efficiency to reduce wait times, maintain cleanliness, and ensure consistent product quality across branches.
