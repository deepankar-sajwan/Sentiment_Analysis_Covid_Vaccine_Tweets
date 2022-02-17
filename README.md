# Sentiment_Analysis_Covid_Vaccine_Tweets
Sentiment Analysis of Covid-19 Vaccine Tweets

Sentiment Analysis of covid vaccination tweets in India and building classification models using various algorithms.

Sources of Data: We have used Twitter tweets data. Have extracted tweets using some specific keywords like Covishield and Covaxin.

Libraries used: Numpy, Pandas, Matplotlib, Seaborn, Re, Itertools, Collections, String, NLTK, Sklearn.

Dataset can be taken from here.

For classifying the sentiment these models were used -

Stochastic Gradient Decent
Logistic Regression
Random Forest
XGBoost
Support Vector Machines
Naive Bayes

Workflow is as follows -


1. Review Dataset - First, we will determine the dataset needed and then define the objective and scope of the project. We will perform data exploration to know about data and to discover patterns, spot anomalies, test hypotheses and check assumptions with the help of summary statistics and graphical representations.

2. Data Pre-Processing - Data Pre-Processing is a step in which we make data suitable for analysis in this we do normalization, removing anomalies and data redundancy.

3. Tokenizer and Stop words removal - The tweets will now be converted into tokens and will remove stop words from the text and then we join the tokens again to get it in the form of tweets.

4. Transformer - We have performed count vectorizer which is a method to convert text to numerical data. Count vectorizer makes it easy for text data to be used directly in machine learning and deep learning models such as text classification.

5. Classification - We have used Classification predictive modeling which involves assigning a class label to input examples. Binary classification refers to predicting one of two classes and multi-class classification involves predicting one of more than two classes. Multi-label classification involves predicting one or more classes for each example and imbalanced classification refers to classification tasks where the distribution of examples across the classes is not equal.

6. Evaluation - Classification predictive modeling algorithms are evaluated based on their results. Classification accuracy is a popular metric used to evaluate the performance of a model based on the predicted class labels. Classification accuracy is not perfect but is a good starting point for many classification tasks.

