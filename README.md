### Sentiment-Analysis - Movie-Reviews
#### This project aims to perform sentiment analysis on movie reviews to classify them as positive or negative.
Project Overview::

Sentiment analysis is a natural language processing (NLP) technique used to determine the sentiment expressed in text. In this project, we analyze movie reviews to predict whether they are positive or negative.

About the Dataset::
The dataset used for this project is a collection of movie reviews (50,000) records. It includes two columns:
- `Review`: The text of the movie review.
- `Sentiment`: The sentiment label (positive or negative).
  
The steps included in the Project are::

1.) Importing required Libraries.

2.) Text Normalization/ Removing HTML code and Extra noise.

3.) Removing Special Characters and stemming.

4.) Removing stopwords.

5.) Bags of words ( convert texts to numerical bags).

6.) Converting text documents to matrix TFIDF.

7.) Labeling and Splitting the sentiment data.

8.) Performed Logistic and Naive Bayes machine learning models.

Conclusion::
This project demonstrates how to perform sentiment analysis on movie reviews using machine learning techniques. The results show that Logistic Regression can effectively classify reviews as positive or negative based on their text content. The code includes the Logistic Regression and Naive Bayes Model's precision, recall, f1-score, and accuracy for better analysis and comparison.
