## SMS_Detection NLP Classification

Data from Kaggle SMS spam collection Database: https://www.kaggle.com/uciml/sms-spam-collection-dataset

The python notebook includes experiments with Word2Ve, Count Vectorizer, Word Embedding, Elmo Embedding with Random forest and different Neural Netowrk Models.
![Image description](https://github.com/TommyJiang91/SMS_Detection/blob/master/Result.png)

Findings:
For this specific dataset, context of the corpus is more important than the content of the corpus when degerming the label. Therefore, Elmo embedding has much better performance than the Count Vectorizer.
