Social Media Sentiment Analysis


Introduction
This report outlines the process and results of a sentiment analysis conducted on a dataset of tweets. The objective is to understand public sentiment towards various games by preprocessing the text data, extracting sentiment scores, and visualizing sentiment trends.

Dataset
The dataset used in this analysis is a CSV file containing tweets related to various games. The relevant columns in the dataset are:

id: Unique identifier for each tweet
game: The game being referenced
sentiment: Manually annotated sentiment (not used in automated analysis)
text: The text content of the tweet

Preprocessing

Steps Involved:
Downloading Necessary NLTK Resources:
Stopwords: Common words to be excluded from analysis (e.g., 'the', 'and')
Punkt: Tokenizer model
WordNet: Lemmatizer for reducing words to their base forms

Preprocessing Function:

URL Removal: All URLs are removed using regex.
Mentions and Hashtags Removal: Mentions (e.g., @user) and hashtags are removed.
Tokenization: The text is split into individual words (tokens).
Stopwords Removal and Lemmatization: Common stopwords are removed, and remaining words are lemmatized.




Observations
The sentiment score distribution reveals that the majority of tweets fall into a neutral to slightly positive range, with fewer tweets showing extreme positive or negative sentiment.
Positive Examples: Tweets generally expressing joy or satisfaction.
Negative Examples: Tweets expressing frustration or disappointment.
Neutral Examples: Tweets that are more factual or contain mixed sentiments.
Conclusion
The sentiment analysis on the dataset of tweets provides valuable insights into public opinion regarding various games. The preprocessing steps ensure that the text data is clean and suitable for sentiment extraction, and the use of VADER sentiment analysis allows for accurate sentiment scoring. Visualization of sentiment trends aids in understanding the overall public mood and specific areas of interest.

Future Work
Enhancing Preprocessing: Further improvements could include handling slang, emojis, and misspellings.
Deeper Analysis: Exploring specific games or time periods for more detailed sentiment trends.
Cross-Platform Analysis: Comparing sentiment across different social media platforms.