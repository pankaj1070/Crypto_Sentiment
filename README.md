# Module_12_Challenge_Crypto_Sentiment

Unit 12—Tales from the Crypto

Background
In this assignment, I applied natural language processing to explain the sentiment in the latest news articles featuring Bitcoin and Ethereum. I also fundamental NLP techniques to better understand the other factors involved with the coin prices such as common words and phrases and organizations and entities mentioned in the articles.

The assignment is divided into 3 parts:

Sentiment Analysis
Natural Language Processing
Named Entity Recognition

1. Sentiment Analysis

Newsapi was used to pull the latest news articles for Bitcoin and Ethereum.

From this data a DataFrame of sentiment scores for each coin was created.

Q: Which coin had the highest mean positive score?

A: Ethereum had the highest mean positive score of 0.079 compared to BTC score of 0.074.

Q: Which coin had the highest compound score?

A: Ethereum had the highest compound  score of 0.86 compared to Bitcoin score of 0.80.

Q. Which coin had the highest positive score?

A:  Both BTC and ETH had highest positive score of 0.249.

2. Natural Language Processing

Using tokenization and ngrams, the following word cloud was generated for BTC and ETH

![btc_WordCloud](C:/Users/panka/NLP_Aug11/btc_WordCloud.png)

![eth_WordCloud](C:/Users/panka/NLP_Aug11/eth_WordCloud.png)

3. Named Entity Recognition

In this excercies, i used NEM for BTC and ETH and visualize the text with SPACY.

