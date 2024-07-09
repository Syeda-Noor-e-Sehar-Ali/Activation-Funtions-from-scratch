# Activation-Funtions-from-scratch
Implementing activation functions from scratch involves creating mathematical functions that introduce non-linearity into neural networks:

Sigmoid Function: Maps input values to a range between 0 and 1, suitable for binary classification tasks but prone to vanishing gradients.

ReLU (Rectified Linear Unit): Sets negative values to zero and keeps positive values unchanged, widely used for hidden layers due to its simplicity and effectiveness in preventing vanishing gradients.

Tanh Function: Similar to the sigmoid but maps values to a range between -1 and 1, often used in recurrent neural networks (RNNs) for its zero-centered output.

Implementation: These functions are implemented using basic mathematical operations like exponentiation and division, ensuring they can be efficiently computed during forward propagation in neural networks.

Choice: The choice of activation function impacts the network's learning ability, gradient flow, and ability to handle different types of data and tasks effectively.
