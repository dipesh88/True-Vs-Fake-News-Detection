# True-Vs-Fake-News-Detection

Import dataset from True vs Fake.zip in collab/ kaggle 

WHY FAKE NEWS IS A PROBLEM?
Fake news is defined as misinformation, disinformation, or mal-information that spreads by word of mouth, conventional media, and, more recently, digital modes of communication such as manipulated films, memes, unconfirmed adverts, and social media disseminated rumours. Fake news on social media has become a severe concern, with the potential for it to lead to mob violence, suicides, and other negative outcomes as a result of disinformation propagated on social media.

Motivation: In this ever increasing social world we see lots of news circulating may it be on social media platforms or on the internet across the globe. So there is a need to classify how can one be sure whether the news is true i.e. is genuine and can be trusted upon from our existing Machine Learning Models and Deep Learning Algorithms. We have also worked on a reasearch of how various social networking sites likeTwitter make their algorithm work to get to know the actual facts about a particular news which helped us carrying this idea forward.

Use Case: To visualize, classify, predict and compare various models/ prepocessing algorithms to check whether a news is true or fake based on a given dataset.

Data Sets

https://www.kaggle.com/datasets/clmentbisaillon/fake-and-real-news-dataset
https://www.kaggle.com/datasets/sandreds/googlenewsvectorsnegative300

Final Results: Along with comparison from other top models Based on the chosen model's accuracy.

By selecting lbfgs as the solver and increasing the maximum number of iterations to 200, we can get an accuracy of 90.77 percent on the testing data for Logistic Regression with spaCy vectors as input features.
With spaCy vectors as input features, the decision tree classifier achieves an accuracy of 85.51 percent.
Logistic Regression with textual data as an input feature and Count Vectorizer and TFIDF Transformer in pipeline achieves 98.93% accuracy.
A Decision Tree Classifier using textual data as an input feature and Count Vectorizer and TFIDF Transformer in the pipeline achieves 99.63 percent accuracy.
Using 1000 input features, an artificial neural network constructed with keras and tensorflow backend with the Sequential Model and dense layers achieves an accuracy of 99.28 percent.
An Artificial Neural Network built using Keras and Tensorflow backends with the Sequential Model and dense layers achieves an accuracy of 99.21 percent on testing data with 10000 input features. Based on the F1-scores of the selected model, we can calculate the number of false positives and false negatives. Overall, we get an accuracy of 98.93%.
By selecting lbfgs as the solver and increasing the maximum number of iterations to 200, we can obtain a f1-score of 90.42 percent on the testing data for Logistic Regression with spaCy vectors as input features.
A decision tree classifier with spaCy vectors as input features achieves a f1-score of 84.49 percent.
Logistic Regression with textual data as an input feature and Count Vectorizer and TFIDF Transformer in the pipeline yields a f1 of 98.81%.
A Decision Tree Classifier using textual data as an input feature and Count Vectorizer and TFIDF Transformer in the pipeline produces a f1-score of 99.61 percent.
Keras with Tensorflow backend Artificial Neural Network with Sequential Model and Dense Layers supply us with a f1-score of 99.25 percent on the testing data with 1000 input features.
An artificial neural network built using Keras and Tensorflow backends with the Sequential Model and dense layers achieves a f1-score of 99.17 percent on testing data with 10000 input features. Also, an F1 score comparable to that of accuracy demonstrates how accurate our model is in forecasting.
values by learning whether it is real or false news via model training

Future Work:

Gathering specific news-related tweets.
Using the same Decision Tree Classifier and pipeline, we will forecast whether or not this is false news.

Another suggestion is to utilise the same for the credibility score assignment of a certain tweet, which is slightly different from this.

Conclusions: Using Pre-Trained Word2Vec Vectors in a pipeline with we've achieved maximum accuracy, recall and F1 score of about 99%, but there is always room for improvement. Various things, such as tweaking the hyperparameters, can be done in the future to improve the accuracy and f1 score based on another dataset. Use of tensors may enhance the overall results.
