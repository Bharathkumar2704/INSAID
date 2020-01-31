# <h1>INSAID
project which i done during my course period
#  <h2>EDA
- It is a way of visualizing, summarizing and interpreting the information that is hidden in rows and column format.
- used winequality csv file in project
![Wine bottle](https://c1.staticflickr.com/5/4124/5096953439_5a41df8055_b.jpg)
#  <h2>Machine Learning Foundation
 - Linear regression
 - Logistic Regression
 - Decision tress
 - Random forest
 - Model evalution
 - used avacado csv file to done a project
  
 ![Avacado](https://cleananddelicious.com/wp-content/uploads/2016/03/Avocad0-CD.jpg)
#  <h2>Machine Learning Intermediate
 - KNN
 - K means
 - SVM
 - Naive bayes
 - PCA
 - used iris dataset to done a project
  ![Iris](https://images.unsplash.com/photo-1554495287-7a2b9869e4a4?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&w=1000&q=80)

-----------------


# Term 1 - EDA
- Exploratory Data Analysis
- **.head()** function of pandas library which returns first five observations of the data set.Similarly **.tail()** returns last five observations of the data set
- found out the total number of rows and columns in the data set using **.shape**
- use the DataFrame **.info()** method to check out data types, missing values
- The **describe()** function in pandas is very handy in getting various summary statistics
- Python has a visualization library ,**Seaborn** which build on top of matplotlib
- find correlations using pandas **.corr()** function and can visualize the correlation matrix using a heatmap in seaborn


------------------

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



----------------------



# <h1> Machine Learning Intermediate
- Principal Component Analysis- Dimensionality Reduction 
- KNN - (K- Nearest Neigbour)-classification
- Naive Bayes Classifier-classification
- K-means Clustering Techniques-clustering
- Support Vector Machines (SVM)-classification
# <h2> Principal Component Analysis- Dimensionality Reduction 
  Principal Component Analysis (PCA) is a technique used to emphasize variation and bring out strong patterns in a dataset.
To perform dimensionality reduction while preserving as much of the randomness in the high-dimensional space as possible
PCA is mainly concerned with identifying correlations in the data.

# <h2> KNN - (K- Nearest Neigbour)-classification
  A powerful classification algorithm used in pattern recognition.An object (a new instance) is classified by a majority votes for its neighbor classes.The object is assigned to the most common class amongst its K nearest neighbors.(measured by a distant function )Distance Measures
- **𝐸𝑢𝑐𝑙𝑖𝑑𝑒𝑎𝑛 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑒 ∶ 𝑑 𝑥, 𝑦 = 𝑥𝑖 − 𝑦𝑖 2**
- **𝑆𝑞𝑢𝑎𝑟𝑒𝑑 𝐸𝑢𝑐𝑙𝑖𝑑𝑒𝑎𝑛 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑒 ∶ 𝑑 𝑥, 𝑦 = 𝑥𝑖 − 𝑦𝑖 2**
- **𝑀𝑎𝑛ℎ𝑎𝑡𝑡𝑎𝑛 𝑑𝑖𝑠𝑡𝑎𝑛𝑐𝑒 ∶ 𝑑 𝑥, 𝑦 = |(𝑥𝑖 − 𝑦𝑖)|**
  
  
![KNN](https://image.slidesharecdn.com/knnfinal-170405165846/95/knearest-neighbor-classifier-16-638.jpg?cb=1494618790)

# <h2> Naive Bayes Classifier-classification
  predicts categorical class labels.classifies data (constructs a model) based on thetraining set and the values (class labels) in a classifying attribute and uses it in classifying new data
Statistical method for classification.
Supervised Learning Method.Can solve problems involving both categorical and continuous valued attributes.

# <h2> K-means Clustering Techniques-clustering
  K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.
Kmeans algorithm is an iterative algorithm that tries to partition the dataset into Kpre-defined distinct non-overlapping subgroups (clusters) where each data point belongs to only one group
  
![K means](https://i.ytimg.com/vi/_aWzGGNrcic/hqdefault.jpg)

# <h2> Support Vector Machines (SVM)-classification
  In machine learning, support vector machines are supervised learning models with associated learning algorithms that analyze data and recognize patterns, used for classification and regression analysis.
Non probabilistic binary linear classifier
For every linearly separable data, there exist infinite number of separating hyperplanes. Hence, we must choose the most suitable one for classification.
Finding the shortest distance(An SVM is simply a linear discriminant which tries to build a hyperplane such that it has a large margin.)
  
![SVM](https://miro.medium.com/max/1280/1*irg_jfdAar9gfe0j-Q04vQ.png)
