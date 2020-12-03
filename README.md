# Cryptocurrency Sentiment Analysis

This file compares two crypto-giants, Bitcoin and Ethereum, across various natural language processing tools. First comparison consisted of a sentiment analysis for each coin's most recent news articles, and used these results in a statistical analysis of the sentiment scores. After, these two non-fiat currencies were compared using a frequency analysis of their top ten bigrams and single word tokens. This process required creating various functions that depended on NLTK and Pandas libraries. Later, the tokens previously generated were used to run a WordCloud to visualize their overall most common repeated words among their list of articles. Lastly, all the articles for each coin were placed into two large corpora, btc_corpus and eth_corpus. Each corpora were then processed through a named entity recognition model, spaCy, and a visual software library, displaCy, to tag and label important words within each corpus.

![Google Images](Images/btc_eth.jpg)

## Sentiment Analysis

### Bitcoin Sentiment Analysis
![](Images/btc_sent.png)
![](Images/btc_stat.png)

### Ethereum Sentiment Analysis
![](Images/eth_sent.png)
![](Images/eth_stat.png)

### Sentiment Analysis Summary
![](Images/Q_A.png)

## Frequency Analysis

### Bitcoin 
![](Images/btc_bigram.jpg)
![](Images/btc_top_10.jpg)

### Ethereum
![](Images/eth_bigram.jpg)
![](Images/eth_top_10.png)

## WordCloud
![](Images/btc_wordcloud.png)

![](Images/eth_wordcloud.png)

## Name Entity Recognition
![](Images/btc_ner.png)
![](Images/eth_ner.png)
