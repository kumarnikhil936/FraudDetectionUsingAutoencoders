# FraudDetectionUsingAutoencoders
Fraud detection is a technique to identify unusual patterns that do not conform to the expected behaviors, and are called outliers.

Autoencoders are unsupervised Neural Networks. They compress the input data to a lower dimension representation. It is a neural network that learns to predict its input. 

The dataset used is the Kaggle dataset for Credit Card Transactions which have some anomalies reported (fraud transactions). It has 284,807 transactions and among them, 492 transactions are labeled as frauds.
https://www.kaggle.com/mlg-ulb/creditcardfraud

The Autoencoder will learn to identify the pattern of the input data. If an anomalous test point does not match the learned pattern, the autoencoder will likely have a high error rate in reconstructing this data, indicating anomalous data.
