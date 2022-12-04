# NewsDetectionSA

Description :

This project has two parts. One code classifies whether a news is fake or real and the other two codes give the sentiment of the news.

Dataset :

ABC news dataset is used. Containing the headline and the text for each news.

Languages and libraries:

This project uses python3, sklearn, numpy, pandas, nltk, wordcloud in jupyter notebook(Anaconda Distribution).

Models and techniques used :

 1. Linear SVC.
 2. Sentiment Analysis is done using Sentiment Analyzer from nltk library, 'compound' polarity score is used for getting the sentiment as 'pos', 'neg', 'neutral'.
 3. CountVectorizer to get frequency of words in each news text for fake or real classification.
 4. TfidfVectorizer to get tf-idf score for each news text for fake or real classification.
