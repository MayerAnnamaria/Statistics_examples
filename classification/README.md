
Classification------------------

1. What are the pros and cons of each model ?
Find the answer in the uploaded pdf.

2. How do I know which model to choose for my problem ?

First you need to figure out whether your problem is linear or non linear. 

If your problem is linear, you should go for Logistic Regression or SVM.

If your problem is non linear, you should go for K-NN, Naive Bayes, Decision Tree or Random Forest.

Then use the with k-Fold Cross Validation to choose between the models.

Then from a business point of view, you would rather use:

- Logistic Regression or Naive Bayes when you want to rank your predictions by their probability. For example if you want to rank your customers from the highest probability that they buy a certain product, to the lowest probability. For this type of question, you should use Logistic Regression if your problem is linear, and Naive Bayes if your problem is non linear.

- SVM when you want to predict to which segment your customers belong to. Segments can be any kind of segments, for example some market segments you identified earlier with clustering.

- Decision Tree when you want to have clear interpretation of your model results,

- Random Forest when you are just looking for high performance with less need for interpretation. 

3. How can I improve each of these models ?

 This is called parameter Tuning. This will allow you to improve the performance of your models, by tuning them. You probably already noticed that each model is composed of two types of parameters:

1) the parameters that are learnt, for example the coefficients in Linear Regression,
2) the hyperparameters.

The hyperparameters are the parameters that are not learnt and that are fixed values inside the model equations. For example, the regularization parameter lambda or the penalty parameter C are hyperparameters. Finding their optimal value is exactly what Parameter Tuning is about.
