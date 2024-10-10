# PySpark Naive Bayes vs Scikit-Learn and Pandas

This repository contains a project that applies the Naive Bayes classification algorithm using PySpark on a large dataset and compares the performance with an implementation using scikit-learn and pandas. The goal is to evaluate the differences in execution time, ease of use, scalability, and accuracy between the two frameworks when dealing with large datasets.


## Overview

Naive Bayes is a probabilistic machine learning algorithm commonly used for classification tasks. In this project, we apply Naive Bayes to a large dataset using two different frameworks:
1. **PySpark**: Known for its distributed computing capabilities, ideal for handling large datasets.
2. **scikit-learn and pandas**: Commonly used for smaller datasets in a non-distributed computing environment.

This project will help to understand the benefits and trade-offs between these frameworks in terms of performance and scalability.

## Dataset

The dataset used for this project should be a large, labeled dataset suitable for classification tasks. The dataset used is [2019 Airline Delays w/Weather and Airport Detail]([https://www.kaggle.com/c/titanic/data](https://www.kaggle.com/datasets/threnjen/2019-airline-delays-and-cancellations).

## Performance Comparison

The key comparison metrics are:
- **Accuracy**: How well each model performs on the test dataset.
- **Execution Time**: Time taken by each framework to load, preprocess, train, and evaluate the model.


