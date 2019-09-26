# MNIST dataset handwritten digit recognition
MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

The goal of the competition is to classify the handwritten digits into 1 of 10 labels namely 0-9. We have a dataset of 42,000 handwritten digits each of which is represented as a 28x28 pixel.

# Data Preparation
We split the dataset into 2 parts: Training Dataset (70%) of the dataset or 29,400 images are used to train our supervised ML models and the remaining 30% i.e. 12,600 images are used to validate the ML models. Since each image is represented as a 28x28 pixel, we have 784 predictors. So we used dimensionality reduction techniques to discard predictors with zero variance. This reduces the dimensionality of the data from 784 predictors to 253 predictors. The predictors are standardized to make sure they have the same scale.

# Performance of different ML algorithms on test dataset
Decision Tree (CART) 0.618

Naïve Bayes 0.821

Random Forest 0.960

K‐Nearest Neighbors 0.969

Boosted Trees 0.990

Support Vector Machines 0.977
