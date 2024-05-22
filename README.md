# Tweets-Sentiment-Analysis

This project aims to analyze the sentiment of tweets from a dataset using Natural Language Processing (NLP) techniques. The analysis is performed using Python libraries such as NLTK, pandas, and seaborn. The sentiment of each tweet is categorized as Positive, Negative, or Neutral.

### Libraries Used
The notebook utilizes the following Python libraries:
1) nltk: Natural Language Toolkit for NLP tasks.
2) pandas: Data manipulation and analysis.
3) matplotlib: Plotting and visualization.
4) seaborn: Statistical data visualization.


### Sentiment Analysis Function
The notebook defines a function tweet_sentiment(sentence) that analyzes the sentiment of a tweet using the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool. The function categorizes tweets as Positive, Negative, or Neutral based on their compound sentiment score.

### Preprocessing Function
Another function preprocess_text(doc) preprocesses the tweet text by tokenizing, converting to lowercase, removing stop words, and lemmatizing the words.

### Visualization
After sentiment analysis, the notebook generates a horizontal bar plot using matplotlib and seaborn. This visualization represents the distribution of tweet sentiments, making it easy to interpret the overall sentiment trends.


## Ensure you have the necessary NLTK libraries downloaded 
1) import nltk
2) nltk.download('vader_lexicon')
3) nltk.download('punkt')
4) nltk.download('stopwords')
5) nltk.download('wordnet')
