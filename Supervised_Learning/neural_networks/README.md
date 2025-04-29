# Neural Networks

## Overview 
Neural Networks are used for supervised learning, both regression and classification tasks.
## How it works
Neural Networks are made of an input layer, a sequence of hidden layers consisting of multiple single neurons, and an output layer.

Each input signal gets scaled by the first layer weights, which in turn is passed into an activation function which forwards this value into the next layer.

The process continues to take place through each layer in the network until an output value is arrived at. 
This process of passing a signal through the layers creates a hihgly composite function approximating the target function \mathit{f}.

Learning occurs by minimizing the model cost function by adjusting the weights and bias with some variant of gradient descent.