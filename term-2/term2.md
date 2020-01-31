# <h1> Machine Learning Basic
# <h2> Supervising learning
  This algorithm consist of a target / outcome variable (or dependent variable) which is to be predicted from a given set of predictors (independent variables). Using these set of variables, we generate a function that map inputs to desired outputs. The training process continues until the model achieves a desired level of accuracy on the training data
# <h3> Linear Regression
  It is used to estimate real values (cost of houses, number of calls, total sales etc.) based on continuous variable(s). Here, we establish relationship between independent and dependent variables by fitting a best line
 # <h3> Logistic Regression
  It is a classification not a regression algorithm. It is used to estimate discrete values ( Binary values like 0/1, yes/no, true/false ) based on given set of independent variable(s). In simple words, it predicts the probability of occurrence of an event by fitting data to a logit function. Hence, it is also known as logit regression. Since, it predicts the probability, its output values lies between 0 and 1
  # <h3> Decision Tree
  It is a type of supervised learning algorithm that is mostly used for classification problems. Surprisingly, it works for both categorical and continuous dependent variables. In this algorithm, we split the population into two or more homogeneous sets. This is done based on most significant attributes/ independent variables to make as distinct groups as possible

  # <h3> Random Forest
  we’ve collection of decision trees (so known as “Forest”). To classify a new object based on attributes, each tree gives a classification and we say the tree “votes” for that class. The forest chooses the classification having the most votes 
  # <h4> confusion matrix
  A confusion matrix is a table that is often used to describe the performance of a classification model on a set of test data for which the true values are known

![confusion Matrix](https://miro.medium.com/max/712/1*Z54JgbS4DUwWSknhDCvNTQ.png)
  
  
  . | Positive | Negative
------------ | ------------- | -------------
| Postive | TP | FP
| Negative | FN | TN
- TP=True Positive
- FP=False Positive
- FN=False Negative
- TN=True Negative

1.Accuracy = TP+TN/TP+FP+FN+TN

2.Precision = TP/TP+FP

3.Recall = TP/TP+FN

4.F1 Score = 2*(Recall * Precision) / (Recall + Precision)
