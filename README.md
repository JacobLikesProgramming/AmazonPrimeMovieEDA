# AmazonPrimeMovieEDA
This project explores and visualizes user reviews from the Amazon Movie &amp; TV dataset, focusing on understanding patterns in sentiment, word usage, and rating behavior. It combines data cleaning, feature generation, and statistical analysis to uncover trends that drive positive or negative reviews. 

Project Overview

Goal: Understand patterns in Amazon movie/TV reviews and identify keywords or features that predict positive vs. negative feedback.
Dataset: Amazon Movie & TV Reviews (text, rating, helpfulness, timestamps).

Tech Stack: 
Python (Pandas, NumPy)
Matplotlib & Seaborn for visualization
NLTK / Scikit-learn for text processing and feature extraction

Data Preparation

Cleaned and filtered dataset for relevant fields (ratings, text, helpfulness).
Standardized text (lowercasing, punctuation removal, stopword filtering).

Generated metrics such as:
Review length (characters, words)
Helpfulness ratio
Yearly average rating deviation

Feature Generation

Text Features: Word count, punctuation usage, sentiment scores, keyword frequencies.
Keyword Analysis: Identified indicative words using custom functions and chi-square testing.
Sentiment Features: Derived polarity measures using NLTK’s VADER or TextBlob.

Visualizations

Rating distributions and yearly sentiment shifts.
Keyword frequency comparisons between high- and low-rated reviews.
Highlighted reviews with extreme helpfulness or negativity.

Extensions

Topic modeling (LDA/NMF) for discovering common review themes.
Predictive modeling (regression/classification) using extracted features.
Exploration of word embeddings for deeper semantic analysis.

License

© 2025 Jacob Silva. All rights reserved.
This repository is for personal and educational use only.
No part of this code may be used, copied, modified, or distributed without explicit written permission from the author.
