# sentiment-analysis-fin-forecasting
This project has investigated the enhancement of sentiment analysis based on the fuzzy logic algorithm in financial forecasting, using Twitter data and Bitcoin prices as a use case. We develop a sentiment analysis model based on Fuzzy Logic,  which is designed to improve financial time series forecasting models.

## 1. Introduction and Theoretical Approach:
- Overview of the sentiment analysis model and its application in time series forecasting.
- Significance of sentiment analysis in understanding investor mood, predicting market trends, and identifying risks and opportunities.
- Applicability of sentiment analysis to various financial markets, with a specific focus on Bitcoin and data gathered from Twitter.

## 2. Proposed Approach:
- Use of fuzzy logic for sentiment analysis of tweets related to Bitcoin.
- Consideration of factors such as the number of retweets and likes for determining market sentiment.
- Application of sentiment analysis results for predicting price movements and adjusting investment strategy.

## 3. Sentiment Analysis Model Architecture:
- Architecture based on NLP techniques and fuzzy logic.
- Data gathering from social media platforms using methods like web scraping and APIs.
- Microblog preprocessing involving text, hashtag, and emoji analysis.
- Detailed preprocessing steps including tokenization, removal of stopwords, punctuation, and other irrelevant information.

## 4. Polarity Calculation:
- Lexicon-based methods for sentiment analysis using dictionaries and polarity scores.
- Emphasis on the impact of emojis on sentiment analysis accuracy.
- Emoji sentiment score dictionary for sentiment analysis.

## 5. Fuzzy Logic Classifier:
- Use of fuzzy logic and Mamdani fuzzy inference system for sentiment classification.
- Fuzzy sets, membership functions, and IF-THEN rules for modeling human knowledge.
- Classification into categories like strongly positive, positive, neutral, negative, and strongly negative.

## 6. Application of Sentiment Analysis on Tweets for Bitcoin Price Forecasting:
- Two-phase architecture for time series forecasting, combining sentiment features, Bitcoin price history, and indicators.
- Use of long-short-term memory (LSTM) neural networks for accurate and reliable predictions.
- Importance of considering the quality and reliability of sentiment data and Bitcoin indicators.

## 7. Datasets:
- Data collection from Twitter using the snscrape library.
- Collection of Bitcoin daily prices, indicators, and industry insights.
- Time series data preprocessing techniques, including linear interpolation and Min-Max scaling.
- 
## 8. Libraries Used
snscrape: Efficient for web scraping Twitter data beyond the API's limitations.
re (Regular Expression): Used for preprocessing tasks such as removing special characters, URLs, and non-ASCII characters.
nltk (Natural Language Toolkit): Powerful NLP library used for tokenization, stemming, lemmatization, etc.
VADER: Lexicon-based sentiment analysis tool specifically adapted for social media sentiments.
Emoji library: Allows the usage and printing of emojis in Python.
Scikit-Fuzzy: A collection of fuzzy logic algorithms for use in the SciPy Stack.

## 9. Model Implementation
The sentiment analysis model is based on a fuzzy logic model using VADER. The project defines the universe for text, hashtags, and emojis, and utilizes fuzzy logic rules to categorize sentiment into distinct levels (strongly positive, positive, neutral, negative, strongly negative).

## 10.Experimentation and Results
The experiments compare the forecasting model with and without sentiment analysis. Results indicate that incorporating sentiment analysis leads to lower loss values (RMSE, MAPE), demonstrating the positive impact of sentiment analysis on predictive accuracy.

