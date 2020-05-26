## SMS_Detection NLP Classification

### Objective:

The objective for this repo is a revisit to the text classification after the fake job detection project. This time I will experiment different features (Word2vec, Count vectorizer, and Embeddings) with various models (Random Forest model, Neural Network Model, and LSTM model). 

### Data:

The data I used is from Kaggle SMS Spam Collection dataset (https://www.kaggle.com/uciml/sms-spam-collection-dataset), which includes SMS tagged messages that have been collected for SMS spam research purpose. This labeled dataset contains 5,574 messages, among which 747 are spam.


![EDA](https://github.com/TommyJiang91/SMS_Detection/blob/master/images/spam%26ham.png)

### Train test split:

I used stratified train test split and used 90% of total messages for training and the rest 10% for testing. 

### Word Clouds for the spams:

![WordCloud](https://github.com/TommyJiang91/SMS_Detection/blob/master/images/wordc.png)

### Model Results:

![Results](https://github.com/TommyJiang91/SMS_Detection/blob/master/images/Result.png)

### Observations:

1.	For this specific dataset, the context of the corpus is more important than the content of the corpus when it comes to determine the label. Therefore, Embeddings has a much better performance than the Count Vectorizer.

2.	The Neural Network model performs better than Random Forest model in all cases except for Word2Vec features. This might be caused by limited words in the corpus.

3.	For Neutral Network models, the Elmo embedding performs better than the Keras Embedding.
