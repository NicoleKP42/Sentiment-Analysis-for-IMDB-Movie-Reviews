# Sentiment-Analysis-for-IMDB-Movie-Reviews
1.	Problem Setting
In this topic we have analyzed the movie reviews based on the sentiments and
emotions. Through sentiment analysis we will be able to understand a wider public
opinion and quickly gauge their attitudes based on negative and positive feedback.
The rationale behind choosing this problem is to identify how the emotions expressed by a movie watcher correlate with the reviews of the movie.
In our project we will be only considering hugely polarized reviews from a large data set which will help us identify a good or a bad movie based on the negative and positive reviews.

2.	Data description
The dataset is nicely structured and is huge in size which allows us to efficiently train our model and evaluate it. The data format will be a CSV file. There are two attributes in this dataset-
● Review - This attribute contains IMDB movie reviews in the form of sentences.
● Sentiment - This attribute contains two values, positive and negative.

3.	Techniques
The dataset consists of sentences which represent user’s reviews for a particular movie. The technology that we can use to analyze such a dataset is Natural Language Processing, sentiment analysis. With the help of NLP, we can understand the underlying meaning of the sentences and identify the review as positive or negative. To do so we will use Python’s PySpark package which provides us with an API to Apache Spark, with the help of which we can process such a huge set of data. The model that we are planning to use is Logistic regression, Decision Tree, and Naïve Bayes. As we progress with our project, we may change the model type based on how the problem solving goes. We may implement many other model and validation techniques as required by the problem in hand.
