BEHVAIOUR ANALYSIS OF TWEETS OF PTSD INDIVIDUALS.

Objective: The main objective of the project is to identify the patterns in the twitter behaviour of individuals with Post Traumatic Stress Disorder. The project also aims at finding key markers in the tweets of users and also to understand the distinction between the usage pattern of these key markers in the tweets before and after a user is diagnosed with PTSD.

1. The idea is to gather the tweets of individuals who proclaim on Twitter to have been diagnosed with PTSD.
2. Gather the old tweets of individuals with PTSD. 
3. Cleanse the data by removing junk characters, emoticons and create a dataset of all the tweets along the twitter handles.
4. Perform Topic Modeling using LDA and Supervised Anchor Word approach using corex package.
5. Employ a Logistic Regression classifier and a SVM classifier to classify the users into individuals with or without PTSD.
6. Validate the classifier by computing Precision, Recall, and comparing AUC in a Receiver operating characteristic curve of the classifiers.
7. Use Cross validation method to test the built classifer on a test set of tweets.
