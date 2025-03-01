# Twitter Sentiment Analysis Project

## Overview
This Jupyter Notebook project performs sentiment analysis on Twitter reviews using Python libraries such as pandas, NumPy, TextBlob, and WordCloud. The analysis includes data preprocessing, sentiment polarity calculation, and visualization of positive comments through a word cloud.

## Features

- Data Loading and Cleaning: Reads a CSV file containing Twitter reviews, handles missing values, and preprocesses the text data.
- Sentiment Analysis: Utilizes TextBlob to compute the polarity of each review, categorizing them as positive, neutral, or negative.
- Data Visualization: Generates a word cloud to visualize the most frequent words in positive reviews.

## Setup Instructions

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/keyur/Twitter_Review_Sentiment_Analysis.git

2. **Install package required**:
   ```bash
   pip install numpy pandas matplotlib pillow textblob wordcloud tkinter

## Dependencies
- pandas: Data manipulation and analysis.
- numpy: Numerical operations.
- matplotlib: Data visualization.
- pillow: Image processing.
- textblob: Text processing and sentiment analysis.
- wordcloud: Word cloud generation.
- tkinter: GUI for user input.

## Notes
- Ensure that the twitter_training.csv file is in the same directory as the Jupyter Notebook or provide the correct path to the file.
- Customize the word cloud generation by adjusting the number of words or modifying the stopwords as needed.
- The sentiment analysis categorizes reviews based on polarity scores: positive (polarity > 0), neutral (polarity = 0), and negative (polarity < 0).

