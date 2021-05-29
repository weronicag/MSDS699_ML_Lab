# Predicting Spam vs. Ham E-mails

I built a Random Forest model that predicts spam vs. ham emails. The data is from UCI Machine Learning Repository, found here https://archive.ics.uci.edu/ml/datasets/spambase. The dataset denotes spam (1) or ham(0) i.e (unsolicited commercial e-mail). The features are primarily related to a word or character frequency and aggregate features related to uninterrupted capital letter sequences. 

The goal is to predict spam vs. non-spam emails - Moreover, how can the model detect as many true positives (correctly classified spam emails) while limiting false positives (wrongly classified spam emails). My approach to this task was to optimize the f1 score through RandomizedSearchCV. 

The results:
- 10 False Postives and 20 False Negatives. 
- Precision Score of 0.965
- F1 score of 0.949 

Further improvements of this model will limit False Postives. 
