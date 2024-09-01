# Mobile App Negative Review Analysis

## Project Overview

This project aims to analyze and categorize negative reviews for a mobile app on the Google Play Store. Using K-means clustering and Natural Language Processing (NLP) techniques, we sort text data from negative reviews into meaningful categories to help identify areas for improvement in the app.

## Data

The analysis uses a dataset `reviews.csv` containing:

- `content`: Text content of each review
- `score`: User-assigned score for the review (integer from 1 to 5)

## Methodology

1. **Data Preprocessing**: 
   - Filter negative reviews (scores < 3)
   - Clean and tokenize review text
   - Remove stopwords and apply stemming/lemmatization

2. **Feature Extraction**:
   - Convert text data to numerical features using TF-IDF

3. **K-means Clustering**:
   - Apply K-means algorithm to group similar reviews
   - Determine optimal number of clusters

4. **Analysis**:
   - Identify common themes in each cluster
   - Extract key phrases or words representing each category

## Tools Used

- Python
- scikit-learn for K-means clustering
- NLTK for NLP tasks
- Pandas for data manipulation

