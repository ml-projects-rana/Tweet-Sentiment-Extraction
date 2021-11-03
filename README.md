# Tweet-Sentiment-Extraction

# 1. Business Problem 

With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company or a person's brand for being viral (positive) or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But which words actually lead to the sentiment description? In this problem we need to pick out the part of the tweet (word or phrase) that reflects the sentiment.

# 2. Source of Data
It is a Kaggle competition. In this competition we have extracted support phrases from Figure Eight's Data for Everyone platform. 

# 3. Data Overview 
It consists of two data files.train.csv with 27481 rows and test.csv with 3534 rows.

List of columns in the dataset :

textID: unique id for each row of data.

text: contains text data of the tweet.

sentiment: sentiment of the text (positive/negative/neutral).

selected_text: phrases /words from the text that best supports the sentiment.

# 4. Performance Metrics
The metric in this problem is the word-level Jaccard score. Jaccard Score or Jaccard Similarity is defined as size of intersection divided by size of union of two sets.



