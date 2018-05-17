# Confusion-Matrix
How to read Confusion Matrix?

Notes from the book: O'Reilly Hands-on Machine Learning

**Confusion Matrix**   
One good way to evaluate the performance of a classifier is to look at the **confusion matrix**. The general idea is to count the number of times instances of class A are classified as class B.   

My purpose is to show how to read confusion matrix, so for this, I will use the MNIST dataset and create a sub-train and test set that only has 5s. So we will have two classes: 5s or not-5s. Then we will train the Stochastic Gradient Descent classifier and look at the confusion matrix to measure the performance.  
