## Goal :
From a dataset containing various Subjects of emails which are classified as either Spam or as Ham (Not Spam). <br/>We are required to predict whether given an Email subject whether it is Spam or Ham.

## How we Implemented it :
We implemented it by first using CountVectorizer on the Text of email and after that we applied the MultinomialNB method from the NaiveBayes Classifier.

## What is Naive Bayes:
It is a classification technique based on Bayes' Theorem with an assumption of independence among predictors. In simple terms, a Naive Bayes classifier assumes that the presence of a particular feature in a class is unrelated to the presence of any other feature.

## Python Libraries used: 
 pandas, numpy, CountVectorizer and MultinomialNB from sklearn
 
 ## What does CountVectorizer do:
 Convert a collection of text documents to a matrix of token counts
 This implementation produces a sparse representation of the counts using scipy.sparse.csr_matrix.
 If you do not provide an a-priori dictionary and you do not use an analyzer that does some kind of feature selection then the number of features will be equal to the vocabulary   size found by analyzing the data.
 
