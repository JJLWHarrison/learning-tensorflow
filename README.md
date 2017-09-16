# Tensorflow and neural networks

This repository contains some notebooks which document my efforts to learn about tensorflow generally, and neural networks in particular.

* [tf-logistic-regression.ipynb](tf-logistic-regression.ipynb) - Demonstrates 2d and 3d logistic regression in tensorflow, or, in other words, fitting a single neuron with a sigmoid activation function to a binary training set with gradient descent. The three dimensional example demonstrates how the technique would generalize to an arbitrary number of input dimensions. Both examples are similar to training a [perceptron](https://en.wikipedia.org/wiki/Perceptron) (not to be confused with a [multilayer perceptron](https://en.wikipedia.org/wiki/Multilayer_perceptron)), except that the activation functions are sigmoids instead of the heaviside step function and gradient descent is used to train the model. 

* [tf-multilayer-perceptron.ipynb](tf-multilayer-perceptron.ipynb) - Demonstrates construction of a two layer perceptron with an arbitrary number of inputs and outputs. The model is then applied to a few datasets and the behaviour is visualised.

* [tf-kmeans.ipynb](tf-kmeans.ipynb) - Performs k-means clustering on two and three dimensional datasets in tensorflow.

