# Twitter-Sentimental-analysis
 It is a Natural Language Processing Problem where Sentiment Analysis is done by Classifying the Positive tweets from negative tweets by machine learning models for classification, text mining, text analysis, data analysis and data visualization.
## Abstract
The goal of this project was to predict sentiment for the given Twitter post using Python. Sentiment analysis can predict many different emotions attached to the text, but in this only 2 major were considered: positive and negative. The data within training dataset was highly skewed, which greatly impacted on the difficulty of building good classifier. After creating a lot of custom features and using some built-in function, utilizing bag-of-words representations and applying the naive bayes algorithm, the classification accuracy at level of 94% was achieved.

## Tweets Preprocessing and Cleaning
The preprocessing of the text data is an essential step as it makes the raw text ready for mining, i.e., it becomes easier to extract information from the text and apply machine learning algorithms to it. If we skip this step then there is a higher chance that you are working with noisy and inconsistent data. The objective of this step is to clean noise those are less relevant to find the sentiment of tweets such as punctuation, special characters, numbers, and terms which don’t carry much weightage in context to the text.

## Story Generation and Visualization from Tweets
we will explore the cleaned tweets text. Exploring and visualizing data, no matter whether its text or any other data, is an essential step in gaining insights. 

## Vectorization and Model Selection
We used well-known techniques for vectorization of words in Natural Language Processing: CountVectorization and Tf-IDF transformation.
After vectorizing our sting data to numerical values in order to feed it to a machine learning algorithm. We choose naive bayes classifier for this binary classification since it is the most common algorithm used in NLP.

This code is prepared Using Jupyter Notebook.
