# Sentiment_Analysis_of_Tweets
My attempt at analyzing the tweets in order to understand the social media behavior of individuals suffering from PTSD

1. The idea is to gather the tweets of individuals who proclaim on Twitter to have been diagnosed with PTSD.
2. Gather the old tweets of individuals with PTSD. 
3. Cleanse the data by removing junk symbols, emoticons, non-numeric values and create a dataset of all the tweets along the twitter handles.
4. Use Bag of Words approach for Feature Selection and utilize Linguistic Inquiry Word Count (LIWC library) in python to draw social and psychological insights from the tweets data.
5. Employ a Logistic Regression classifier and a SVM classifier to classify the users into individuals with or without PTSD.
6. Validate the classifier by computing Precision, Recall, and comparing AUC in a Receiver operating characteristic curve of the classifiers.
7. Use Cross validation method to test the built classifer on a test set of tweets.
