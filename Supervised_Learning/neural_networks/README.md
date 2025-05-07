# Neural Networks

Neural Networks are used for supervised learning, both regression and classification tasks.
## How it works
Neural Networks are made of an input layer, a sequence of hidden layers consisting of multiple single neurons, and an output layer.

Each input signal gets scaled by the first layer weights, which in turn is passed into an activation function which forwards this value into the next layer.

The process continues to take place through each layer in the network until an output value is arrived at. 
This process of passing a signal through the layers creates a hihgly composite function approximating the target function f.

Learning occurs by minimizing the model cost function by adjusting the weights and bias with some variant of gradient descent.


## Application
This module builds a fully connected feedforward neural network from scratch in Python to classify grayscale images of clothing items from the Fashion MNIST dataset. 

The implementation's main components include:
- One-hot encoding of labels

- Sigmoid activation functions

- Mean Squared Error (MSE) loss

- Forward pass to generate predictions

- Backpropagation with Stochastic Gradient Descent (SGD) for training

- Evaluation metrics including accuracy and a confusion matrix

The model is trained on the Fashion MNIST dataset available via keras, a deeplearning API, and it includes grayscale images sized 28x28 of 10 clothing categories.

In the end, I achieved the final test accuracy of 85%, and observed the MSE loss drop consistently across training epochs. The confusion matrix revealed the model performs well overall, but with confusion between similar classes like T-shirts vs. tops or sneakers vs. ankle boots.

### Dependencies

Make sure to install the required libraries.
```bash 
pip install numpy matplotlib tensorflow scikit-learn
