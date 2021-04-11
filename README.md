# Cryptocurrency Sentiment Analysis

This page compares two crypto-giants, Bitcoin and Ethereum, across various natural language processing tools. First comparison consisted of a sentiment analysis for each coin's most recent news articles, and used these results in a statistical analysis of the sentiment scores. After, the two coins were compared using a frequency analysis of their top ten bigrams and single words from each article. Each bigram and single word were placed in what is refered to as tokens. This process required creating various functions that depended on NLTK and Pandas libraries. These tokens were then used to run a WordCloud to visualize their overall repetition among the various articles. Lastly, all the articles  were placed into two large corpora, btc_corpus and eth_corpus. Each corpus was then processed through a named entity recognition model, spaCy, and a visual software library, displaCy, to tag and label important words within each corpus.

![Google Images](Images/btc_eth.jpg)

## Sentiment Analysis

### Bitcoin Sentiment Analysis
![](Images/btc_sent.png)
<br />
![](Images/btc_stat.png)

### Ethereum Sentiment Analysis
![](Images/eth_sent.png)
<br />
![](Images/eth_stat.png)

### Sentiment Analysis Summary
![](Images/Q_A.png)

## Frequency Analysis

### Bitcoin 
![](Images/btc_bigram.jpg)
<br />
![](Images/btc_top_10.jpg)

### Ethereum
![](Images/eth_bigram.jpg)
<br />
![](Images/eth_top_10.png)

## WordCloud
![](Images/btc_wordcloud.png)
<br />
![](Images/eth_wordcloud.png)

## Name Entity Recognition
![](Images/btc_ner.png)
<br />
![](Images/eth_ner.png)
