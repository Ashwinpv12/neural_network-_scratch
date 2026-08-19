# neural_network-_scratch
A simple, two-layer feedforward neural network built entirely from scratch using only Python and NumPy.  
This project was created to understand the underlying mathematics of machine learning. No deep learning frameworks (like TensorFlow, Keras, or PyTorch) were used. Everything—from weight initialization and forward propagation to calculating derivatives for backpropagation and gradient descent—is hardcoded using linear algebra.

The network is trained on the classic MNIST dataset to classify images of handwritten digits (0-9).


Built from Scratch: Pure Python and NumPy implementation.
Math-Focused: Implements mathematical concepts directly in code, including:
<br>Matrix dot products
ReLU (Rectified Linear Unit) activation for the hidden layer
Softmax activation for the output layer
One-hot encoding for categorical labels
Gradient Descent and Backpropagation for calculating loss derivatives and updating weights/biases.
Visual Testing: Uses matplotlib to render the handwritten digit alongside the AI's prediction.
