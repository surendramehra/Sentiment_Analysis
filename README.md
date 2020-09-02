# Tweet-Sentiment-Analysis
Sentiment Analysis / Opinion Mining for provided data in NLTK corpus using Naive Bayes Classifier Algorithm
Sentiment-Analysis-NLTK
Basic Algorithm:
NaiveBayesClassifier was used as the opinion classifier.

The dataset included a list of sentences.

The sentences was converted to form bag of words.

75% of the corpora was used as the Training set.

Rest 25% was used to test the Classifier module.

Modifying the algorithm:
Using first 'N' frequent words can increase the accuracy.

Note : N should be changed along a certain range to check the peak point.

There can be sentences like :

This is not good

Bigrams (pair of words) can be used to include {'not', 'good'} in the bag of words.

Using bigrams can exponentially increase the algorithmic accuracy.

For opinion mining, including emoticons can make the Classifier a lot better.

Pickle can be used to save the training model once and for all.

The algorithm can be trained once and classifying the data will take no time henceforth.

Analysis of movie_reviews corpora:
Accuracy on modified algorithm: 72.8

Accuracy with algorithm including bigrams: 84.8

Analysis of twitter_samples corpora:
Accuracy with algorithm excluding emoticons: 76.9

Accuracy on modified algorithm: 97.35

Accuracy with algorithm including bigrams: 99.1
