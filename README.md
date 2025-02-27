# IMDB-Review-Sentiment-LSTM-GRU

**IMDb Sentiment Analysis with LSTM and GRU**

This project leverages deep learning models, specifically Long Short-Term Memory (LSTM) and Gated Recurrent Units (GRU), to perform sentiment analysis on IMDb movie reviews. The objective is to classify the sentiment of each review as positive or negative using these powerful sequential models.




**Models Used:**


LSTM (Long Short-Term Memory): A type of Recurrent Neural Network (RNN) capable of learning long-range dependencies in sequence data, making it effective for tasks like sentiment analysis.


**Train Accuracy: 97%**


Test Accuracy: 88%



**GRU (Gated Recurrent Unit):** A simpler variant of LSTM that performs similarly while being more computationally efficient. GRUs are less prone to overfitting on smaller datasets.


Train Accuracy: 93%


Test Accuracy: 89%



**Key Highlights:**


Text Preprocessing: The reviews are tokenized, padded, and embedded to create a meaningful representation of the text for the model.


Performance Comparison: The LSTM model achieved slightly higher training accuracy, while the GRU model performed slightly better on the test data, indicating its ability to generalize better to unseen data.


Dataset: IMDb movie reviews dataset containing a balanced set of positive and negative reviews.



**Libraries and Tools:**


Python


TensorFlow/Keras


Numpy, Pandas


Scikit-learn



This project demonstrates how to apply deep learning techniques to real-world text classification tasks, showcasing the strengths of LSTM and GRU in handling sequential data.

