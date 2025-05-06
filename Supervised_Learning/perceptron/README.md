# Perceptron
Algorithm for supervised learning of binary classifiers.
## Overview of the Algorithm

Single Layer Perceptron can learn only linearly separable patterns.
It's a simplified model of a biological neuron, simulating one cell's behavior.
A neuron cell gets an input signal -> the signal travels and once it reaches a threshold, the cell activates and gives an output signal.


## Application
For this notebook, a dataset from Kaggle about hotel reservations was used.


We focus on the binary classification task of predicting whether a hotel booking was canceled (`1`) or not (`0`). After converting labels to -1 and 1, we explore different feature pairs such as:
- Number of adults and children
- Lead time and previous cancellations
- Lead time and number of special requests

Through decision boundary plots and error tracking over iterations, we evaluate the performance and limitations of the Perceptron on linearly and non-linearly separable data.
