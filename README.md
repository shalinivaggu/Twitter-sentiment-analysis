# Twitter Sentiment Analysis for #Pushpa2

This project analyzes recent tweets about the movie #Pushpa2, providing sentiment analysis results visualized in an interactive Streamlit app.

## Features

- **Data Collection:**  Fetches recent English tweets about #Pushpa2 using the Tweepy library.
- **Data Processing:** Cleans the tweets (removing URLs, mentions, etc.) and performs sentiment analysis using VADER (NLTK).
- **Interactive Visualization:** Streamlit app to explore:
    - Filtered tweets by sentiment (Positive, Negative, Neutral).
    - Bar chart visualizing sentiment distribution.
    - Word cloud showcasing frequent keywords, revealing topics and themes within the tweets.
- **Data Export:** Saves collected and analyzed data to CSV files (`tweets.csv`, `tweets_cleaned.csv`, `tweets_with_sentiment.csv`).

## Requirements

- Python 3.7+
- Libraries: `tweepy`, `pandas`, `nltk`, `matplotlib`, `streamlit`, `wordcloud`

## Setup

1. **Install Libraries:** `pip install tweepy pandas nltk matplotlib streamlit wordcloud`
2. **Twitter API:** 
    - Create a Twitter developer account and obtain API keys and tokens.
    - Replace placeholders in the code with your credentials.
3. **Run Notebook:** Execute the code cells in the notebook sequentially.

## Usage

1. **Launch Streamlit App:** After running the notebook, a Streamlit app will open in your browser.
2. **Interact:** Use the sidebar filters to select sentiments and explore the filtered tweets and visualizations.


