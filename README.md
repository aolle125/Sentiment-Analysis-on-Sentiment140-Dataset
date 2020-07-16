# Sentiment-Analysis-on-Sentiment140-Dataset

Performed Sentiment Analysis on the Sentiment140 Dataset.
It contains 1,600,000 tweets extracted using the twitter api. 
The tweets have been annotated (0 = negative, 4 = positive) and they can be used to detect sentiment.

Dataset Details:

target: the polarity of the tweet (0 = negative, 2 = neutral, 4 = positive)
ids: The id of the tweet 
date: the date of the tweet 
flag: The query 
user: the user that tweeted 
text: the text of the tweet

Data Pre-Processing:

1. Removing the Stop Words
2. Using Porter Stemmer
3. Padding Sequences so that every tweet has the same size
4. Label Encoding


Using Pre-trained Glove Embeddings on the tweets. GloVe is an unsupervised learning algorithm for obtaining vector representations for words. 
Training is performed on aggregated global word-word co-occurrence statistics from a corpus, 
and the resulting representations showcase interesting linear substructures of the word vector space.

LSTM Long Short Term Memory are a special kind of RNN, capable of learning long-term dependencies, are used for sentiment analysis.
