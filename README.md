# High-Dimensional-Data-and-Gradient-Descent
*Analyzing and overcoming the curse of dimensionality and exploring various gradient descent techniques with implementations in R*

This project was completed in partial fulfilment of the course FOUNDATIONS OF DATA SCIENCE (CS F320) offered during Second Semester 2019-20 at BITS Pilani, Pilani Campus.

The aim of this project was to analyse high dimensional data by identifying and techniques to 

## What are Multivariate Time Series (MVTS)?

In this project we first looked at various problems related to high dimensional data which include:
#### 1. sparsity of data
#### 2. overfitting
#### 3. irrelevant features, and 
#### 4. diminishing effectiveness of distance measures. 

The proposed solutions consist of:
#### 1. Principal Component Analysis (PCA)
#### 2. Kernel PCA, and 
#### 3. Singular Value Decomposition (SVD). 

These solutions were implemented in R and the results obtained clearly indicate their efficacy in overcoming all the problems.

We then shifted our focus to Gradient Descent and realized that we face problems where __*the objective function gets stuck at a local minima for a non-convex loss function*__ or that __*GD runs slow for larger datasets*__. We also observed that the learning rate should be chosen suitably.

A few successful variations of GD exist to overcome these issues such as:
#### 1. Batch Gradient Descent 
#### 2. Stochastic Gradient Descent, and 
#### 3. Mini-Batch Gradient Descent. 

We saw that the cost is often highly sensitive to some directions in parameter space and insensitive to others. The momentum algorithm can mitigate these issues somewhat, but does so at the expense of introducing another hyperparameter.

We then discussed a number of incremental (or mini-batch-based) methods that adapt the learning rates of model parameters. These include: 
#### 1. Nesterov Momentum 
#### 2. AdaGrad, and 
#### 3. Adam

Having implemented these solutions in R, the results suggest that the family of algorithms with adaptive learning rates performed fairly robustly and emerged as clear winners.

The choice of which algorithm to use, at this point, seems to depend largely on the user's familiarity with the algorithm (for ease of hyperparameter tuning).

### Want to know more?
Please read the [report](https://github.com/Vitthal98/High-Dimensional-Data-and-Gradient-Descent/blob/main/FoDS%20Report.pdf) as it contains detailed information about the datasets used, methods implemented, results obtained and further discussion.

For any doubts don't hesitate to contact me at vitthalbhandari98@gmail.com

If you find our work helpful, do not forget to :star: the repository!
