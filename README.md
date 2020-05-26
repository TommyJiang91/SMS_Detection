## SMS_Detection NLP Classification

Data from Kaggle SMS spam collection Database: https://www.kaggle.com/uciml/sms-spam-collection-dataset

The data comes from Kaggle SMS Spam Collection (https://www.kaggle.com/uciml/sms-spam-collection-dataset), the SMS tagged messages have been collected for SMS spam research. This labeled dataset contains 5574 messages, in which 747 are spam.

(https://github.com/TommyJiang91/SMS_Detection/blob/master/Result.png)

Word Clouds for the spams:
![Image description](https://github.com/TommyJiang91/SMS_Detection/blob/master/Result.png)

Model Results:
![Image description](https://github.com/TommyJiang91/SMS_Detection/blob/master/Result.png)

Findings:
For this specific dataset, context of the corpus is more important than the content of the corpus when degerming the label. Therefore, Elmo embedding has much better performance than the Count Vectorizer.
