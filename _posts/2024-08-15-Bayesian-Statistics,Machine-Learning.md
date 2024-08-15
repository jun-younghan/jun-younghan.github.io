---
title : Bayesian statistics, Machine Learning
excerpt : Most important theorem at ML
categories :
        - stduy
        - machine learning
toc : true
author_profile : false
sidebar :
    nav : "counts"
---

# What is Bayesian statistics?

## Conditional Probability
Conditional Probability is the probability of another event occurring when one event occurs.
The probability for k events through the conditional probability is expressed by the following equation.

## Partition
If a set of K is to be a partition of any set S
1. Each set of K must be disjoint.
2. The set of K sets must be exactly S.
   
If K set B is a partition of S, then the following equation must be established for subset A of S.

The probability of A seems like this.


## Bayesian statistics

The Bayesian statistics expression.

The biggest feature of Bayesian statistics is if our data and evidence increases, the more knowledge is updated and improved.
And these features are very useful for machine learning.

# Bayesian statistics and Machine-Learning

## Linear regression
Linear regression can be said that it is to infer the relationship between the independent variable and the dependent variable.


The goal of regression is to minimize the difference between the estimated y and the actual y.


Machine learning gradually learns through various algorithms and finds parameters.
The process of finding parameters is shown through Bayes' theorem as follows.

We know a prior called P(model), and if new data is observed, machine learning is the process of getting a
posterior(P(model | data)) and gradually finding the distribution of p(model) while using it as a prior for the next learning.

## Is it improtant to updating prior?


From the graph above, it can be seen that the performance of the classifier using the Bayesian method can vary significantly.
