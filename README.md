This is a project to classify the polarity (and star rating) based on a review written on Amazon.

I've used a normal bag-of-words vectoriser and TF-IDF, with an SVM and a Naive Bayes classifier, and compared their results.

The final model (SVM classifier with TF-IDF) has an F1-score of 89% at predicting review polarity, and 55% at predicting actual product rating. (Rating classification is done with 5 classes.)
