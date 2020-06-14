# Sentiment Analysis and Natural Language Processing

## Background

In this project, natural language processing is used to understand the sentiment in the latest news articles featuring Bitcoin and Ethereum. Fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.


## Sentiment Analysis

The [newsapi](https://newsapi.org/) is used to pull the latest news articles for Bitcoin and Ethereum and create a DataFrame of sentiment scores for each coin.


## Natural Language Processing

NLTK and Python are used to tokenize the text for each coin and in the process:

1. Lowercase each word
2. Remove punctuation
3. Remove stop words

Ngrams and word frequencies are produced for each coin.

1. ngrams are set to N = 2.
2. The top 10 words for each coin are generated.

Word clouds are generated for each coin to summarize their respective news.

## Conclusions

1. Ethereum's mean positive score of 0.874 exceeded Bitcoin's mean positive score of 0.782.

2. Ethereum's max compound score of 0.848 slightly exceeded Bitcoin's max compound score of 0.802.

3. Ethereum's max positive score of 0.260 exceeded Bitcoin's max positive score of 0.188.

## Resources

[Vader Sentiment Analysis](http://www.nltk.org/howto/sentiment.html)