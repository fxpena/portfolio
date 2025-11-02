---
title: Credit card fraud detection
---
![Fraud data is highly imbalanced](../images/fraud_pie_chart.png)

Fraud can occur in a variety of forms, but machine learning is often the strongest approach to detect fraud. In [this repository](https://github.com/fxpena/fraud_detection), I train and cross-validate ML models to predict credit card fraud. One of the major obstacles for this task is that 98% of card transactions are not fraud. In other words, the dataset is highly imbalanced. Most of my approach can be adapted to training machine learning models for other business cases with highly imbalanced data such as ACH fraud, loan default, purchase conversion, and more.

![Feature with signal about fraud status](../images/log_transactionAmount_by_fraud_status.png)