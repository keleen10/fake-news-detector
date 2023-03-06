# fake-news-detector
A model to accurately classify a piece of news as REAL or FAKE.


This advanced python project of detecting fake news deals with fake and real news. 
Using sklearn, we build a TfidfVectorizer on our dataset. 
Then, we initialize a PassiveAggressive Classifier and fit the model. 
In the end, the accuracy score and the confusion matrix tell us how well our model fares.


In this model I got Accuracy: 92.9%
[[589  49]
 [ 41 588]]
 
 we have 589 true positives, 588 true negatives, 41 false positives, and 49 false negatives.
