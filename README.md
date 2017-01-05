# TwitterSentimentAnalysis-Elections2012
Sentiment Mining for Election Tweets of 2012

This project classifies tweets of Elections held in 2012 as Positive, Negative and Neutral. The Tweets are collected and segregated into two different files containing specific tweets for Obaman and Romney.

Distribution of tweets according to their class in Obama Dataset:

Positive tweets : Around 1900
Negative tweets : Around 1800
Neutral tweets  : Around 1600

There is an almost even distribution of tweets thus providing a fair base for applying machine learning techniques

Distribution of tweets according to their class in Romney Dataset:

Positive tweets : Around 1600
Negative tweets : Around 2800
Neutral tweets  : Around 1000

There is a great imbalance in the number of positive tweets, neutral tweets and negative tweets, therefore oversampling was done to attain a proper balance.

Machine learning tools used : Python 3.5, SciKit learn 18

Machine Learning Algorithms used : MultiNomial NB, Logistic Regression, SVM with Linear kernal, Random Forest, Voting Classifier(NB, Logistic Regression, SVM, RF), AdaBoost on SVM, MultiLayer Perceptron with 10 hidden layers

Results can be found in the file FinalResults.txt
