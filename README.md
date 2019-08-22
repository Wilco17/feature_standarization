# feature_standarization
Feature standarization in linera regression as a menas of optimization preconditioning

The following  naive example may serve as an illustration (alternative to majority of the examples I found) of the benefits of feature standardization in machine learning, whilst at the same time,  giving a rough intuition behind the concept of preconditioning, which is of course, a more complex and sophisticated mathematical tool. 
From now on, we will be working on an standard linear regression problem, but instead of using a closed form solution (the clever thing to do), we will try an iterative method (that seems for instance much like brute force): stochastic vanilla gradient descent algorithm.
