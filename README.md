# Applied-ML
# Homework5 
Design a genetic algorithm to solve the polynomial fitting problem that we did in Homework #1. 
You need to implement a genetic algorithm using BOTH mutation AND crossover operations. You 
need to decide a mutation rate and a crossover rate.  
 
Plot the following in one figure: 1) the original noisy data, 2) the polynomial you obtained in 
Homework  #1,  and  3)  the  polynomial  obtained  from  this  implementation.  Compare  and 
discussion the difference in performance of the two polynomials obtained with two different 
methods. 
# Homework 4
Step 1: use our “titanic” dataset in homework #3, and split data in the same way you did in homework #3 – 80% as training and 20% test sets;
Step 2: Fit a neural network using independent variables ‘pclass + sex + age + sibsp’ and dependent variable ‘survived’. Fill in n/a attributes with the average of the same attributes from other training examples. Use 2 hidden layers and set the activation functions for both the hidden and output layer to be the sigmoid function. Set “solver” parameter as either SGD (stochastic gradient descend) or Adam (similar to SGD but optimized performance with mini batches). You can adjust parameter “alpha” for regularization (to control overfitting) and other parameters such as “learning rate” and “momentum” as needed.
Step 3: Check the performance of the model with out-of- sample accuracy, defined as out-of-sample percent survivors correctly predicted (on test set)
out-of-sample percent fatalities correctly predicted (on test set)
Please try two different network structures (i.e., number of neurons at each hidden layer) and show their respective accuracy.
Step 4: Compare the out-of-sample accuracy (as defined in step 3) with the random forest obtained in homework #3. (You can either use a table or plot the results of the two algorithms in one figure). Explain any difference in accuracy.
Note: There are two options to implement the neural network:
Option 1: use scikit-learn library;
Here is the tutorial: http://scikit-learn.org/stable/modules/neural_networks_supervised.html
Option 2 (bonus: 2 points): implement backpropagation yourself; in your implementation, you better set the following:
(1) the initial weights to be uniformly between [-0.1, +0.1]  
(2) the number of iterations to be around 5000 or more (but not tens of thousand) 
You can choose either option for this homework. You will get 5 bonus points if you choose option 2. No matter what you choose, make sure you know how to update the weights.
