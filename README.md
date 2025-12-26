# ML-Sentiment-Classification
Research Question: How does the performance of neural networks(BI-LSTM & CNN) compare to logistic regression in sentiment analysis on combined Amazon review and Twitter data?

We investigate the performance of Neural Network(NN) models compared to
Logistic regression(LR) in sentiment classification on the combined dataset of Amazon reviews and Twitter tweets. Our classification task is to map each document to
ternary labels(positive, neutral, and negative). The datasets contain 205000 reviews
and around 50000 tweets. A preprocessing pipeline is used to remove noisy and
uninformative data from the raw input. Two feature engineering techniques were applied to transform preprocessed text into numeric vectors: TF-IDF for LR and Word
Embeddings for the NN models. We consider two neural network models: Bidirectional Long Short-Term (Bi-LSTM) and Convolutional Neural Networks (CNN).
We evaluate the performance by using accuracy and averages of the F1-scores as
our metrics. Our analysis results show that while LR performs best for predicting
the neutral sentiment in our dataset, Bi-LSTM yields the highest overall accuracy at
72.8%, slightly followed by CNN at 72.2%, and LR at 71.4%.


Keywords: Sentiment classification, TF-IDF, Word-Embeddings, Logistic Regression,
CNN, LSTM, Amazon reviews, Twitter
