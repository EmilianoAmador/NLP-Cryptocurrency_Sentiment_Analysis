# Cryptocurrency Sentiment Analysis

This activity compares two crypto-giants, Bitcoin and Ethereum, across various natural language processing tools. First comparison consisted of a sentiment analysis for each coin's most recent news articles, and used the results for a statistical analysis of the sentiment scores. After, these two non-fiat currencies were compared through a frequency analysis of their top ten bigrams and single word tokens. This process required creating various functions that depended on NLTK and Pandas library. Later, the tokens previously generated were used to run a WordCloud to visualize their overall most common used words among their articles. Lastly, all the articles for each coin were placed into two large corporas, btc_corpus and eth_corpus. The corporas were then processed through a named entity recognition model, spaCy, and a visual software library, displaCy, to tag and label important words within each corpus.

![Google Images](../Images/btc_eth.jpg)

## Sentiment Analysis

### Bitcoin Sentiment Analysis
![](../Images/btc_sent.jpg)
![](../Images/btc_stat.jpg)

### Ethereum Sentiment Analysis
![](../Images/eth_sent.jpg)
![](../Images/eth_stat.jpg)

### Summary
![](../Images/Q_A.jpg)

## Frequency Analysis

### Bitcoin 
![](../Images/btc_bigram.jpg)
![](../Images/btc_top_10.jpg)

### Ethereum
![](../Images/eth_bigram.jpg)
![](../Images/eth_top_10.jpg)

## WordCloud
![](../Images/btc_wordcloud.jpg)

![](../Images/eth_wordcloud.jpg)

## Name Entity Recognition
![](../Images/btc_ner.jpg)
![](../Images/eth_ner.jpg)
