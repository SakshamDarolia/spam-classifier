# spam-classifier
Helps to classify messages as spam or ham. The 'spam.csv' consists of the data i.e basically text messages labelled as ham or spam.

Brief points:

- The dataset contains messages and was taken from Kaggle. 

- To get the data ready, the punctuation marks and morphological affixes from the messages were removed.

- Used BoW(Bag of Words) approach to get all unique words and applied Tf-Idf transform.

- Used Multinomial Naive Bayes model for prediction and got an accuracy score of about 98.26%.
