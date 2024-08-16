---
title : Bayesian statistics, Machine Learning
excerpt : Most important theorem at ML
categories :
        - study
        - machine-learning
toc : true
author_profile : false
sidebar :
    nav : "counts"
---

# What is Bayesian statistics?

## Conditional Probability
Conditional Probability is the probability of another event occurring when one event occurs.
The probability for k events through the conditional probability is expressed by the following equation.

![image](https://github.com/user-attachments/assets/d8da356f-0e8b-47a6-87f1-782e960dd5e3)

## Partition
If a set of K is to be a partition of any set S
1. Each set of K must be disjoint.
2. The set of K sets must be exactly S.
   
If K set B is a partition of S, then the following equation must be established for subset A of S.

![image](https://github.com/user-attachments/assets/0bc1f27b-16b0-44cc-8399-b154373c5e29)


The probability of A seems like this.

![image](https://github.com/user-attachments/assets/189f492c-0049-4a31-b107-5601d7c471c5)


## Bayesian statistics

The Bayesian statistics expression.

![image](https://github.com/user-attachments/assets/5591ae61-65c8-49e9-b6cd-f03fc9b842f0)

The biggest feature of Bayesian statistics is if our data and evidence increases, the more knowledge is updated and improved.
And these features are very useful for machine learning.

# Bayesian statistics and Machine-Learning

## Linear regression
Linear regression can be said that it is to infer the relationship between the independent variable and the dependent variable.

![image](https://github.com/user-attachments/assets/db1a894c-bc34-4f6d-827b-d0f6e74fd399)


The goal of regression is to minimize the difference between the estimated y and the actual y.


Machine learning gradually learns through various algorithms and finds parameters.
The process of finding parameters is shown through Bayes' theorem as follows.

![image](https://github.com/user-attachments/assets/781f89fe-07a7-4a13-8906-c73e70da4d40)


We know a prior called P(model), and if new data is observed, machine learning is the process of getting a
posterior(P(model | data)) and gradually finding the distribution of p(model) while using it as a prior for the next learning.

## Is it improtant to updating prior?

![image](https://github.com/user-attachments/assets/7fbd51a5-aa9e-43e4-b193-43481ec3ce56)


From the graph above, it can be seen that the performance of the classifier using the Bayesian method can vary significantly.
