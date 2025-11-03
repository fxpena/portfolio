---
title: Credit card fraud detection
---
Fraud detection can prevent millions of dollars in losses depending on the size of the business. In consumer banking, a form of fraud that needs to be mitigated is credit card fraud. I used a publicly available dataset of card transactions from Capital One to train fraud detection models. The model with the best performance on held-out data correctly identified 57.4% of fraud transactions by using a linear support vector machine (SVM) and balancing the training data using synthetic minority oversampling technique (SMOTE). One of the major obstacles for this task is that 98% of card transactions are not fraud (as shown below). In other words, the dataset is highly imbalanced. Beyond this use case, this approach can be applied to other business cases with highly imbalanced data such as ACH fraud, loan default, purchase conversion, and more.

### Go to this [notebook](https://github.com/fxpena/fraud_detection/blob/main/fraud_detection.ipynb) to see the implementation and detailed results of the predictive model.
The repository for the project lives [here](https://github.com/fxpena/fraud_detection)


![Fraud pie chart](/images/fraud_pie_chart.png)

_Pie chart showing the proportion of card transactions that are fraudulent or not._