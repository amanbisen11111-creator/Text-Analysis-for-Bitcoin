# Text-Analysis-for-Bitcoin
Bitcoin News Sentiment & Topic Analysis

This project analyzes Bitcoin-related news from multiple sources to understand trends, sentiments, and popular topics in the cryptocurrency space. The analysis includes data preprocessing, sentiment analysis, topic modeling, and visualization of insights.

Project Overview

Data Collection:

News articles about Bitcoin were collected from various online sources, including CNBC, CoinDesk, CNN, and more.

Key information collected includes article title, link, published date, source, and image.

Data Preprocessing:

Titles were cleaned by converting to lowercase, removing special characters, tokenizing, and removing stopwords.

This step ensures better accuracy in sentiment analysis and topic modeling.

Sentiment Analysis:

Each news title was analyzed to classify sentiment as Positive, Negative, or Neutral.

Helps identify the overall mood of Bitcoin news over time.

Topic Modeling:

Used TF-IDF vectorization and Non-negative Matrix Factorization (NMF) to extract key topics from the news titles.

Top words for each topic were visualized using bar charts and word clouds.

Bigram & Trigram Analysis:

Frequent two-word (bigrams) and three-word (trigrams) combinations were identified to understand popular phrases in Bitcoin news.

Key Insights

Common topics include Bitcoin price predictions, investment trends, Coinbase updates, and regulatory news.

Sentiment distribution shows a mix of positive, neutral, and negative news, with some spikes around major events.

Frequent phrases like "price prediction," "good investment," and "Kevin Durant" indicate trending stories and popular discussions.

Tools & Libraries

Python – main programming language

Pandas – data manipulation

NLTK & TextBlob – text preprocessing and sentiment analysis

scikit-learn – TF-IDF vectorization & topic modeling (NMF)

Matplotlib & WordCloud – visualization of topics and trends

Output

Preprocessed news data in Excel format

Sentiment analysis results with polarity scores and categories

Topic modeling results with top words per topic

Visualizations: word clouds and bar charts for topics

Use Cases

Cryptocurrency market analysis

Tracking news sentiment trends

Identifying popular discussion topics around Bitcoin

Supporting investment and research decisions
