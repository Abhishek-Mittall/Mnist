# Mnist
The MNIST database (Modified National Institute of Standards and Technology database) is a large database of handwritten digits that is commonly used for training various image processing systems. The database is also widely used for training and testing in the field of machine learning.

The MNIST database contains 60,000 training images and 10,000 testing images.
[[source : wikipedia](https://en.wikipedia.org/wiki/MNIST_database)]
<p align="center">
  <img src="https://github.com/Pratham1807/Mnist-1/blob/master/images/img-1.PNG" width="500">
</p>

### MultiLayer Perceptrons(MLP)
A multilayer perceptron (MLP) is a class of feedforward artificial neural network. An MLP consists of at least three layers of nodes: an input layer, a hidden layer and an output layer. Except for the input nodes, each node is a neuron that uses a nonlinear activation function. MLP utilizes a supervised learning technique called backpropagation for training. Its multiple layers and non-linear activation distinguish MLP from a linear perceptron. It can distinguish data that is not linearly separable. 
[[source : wikipedia](https://en.wikipedia.org/wiki/Multilayer_perceptron)]

<p align="center">
  <img src="https://github.com/Pratham1807/Mnist-1/blob/master/images/img-2.PNG">
</p>

In our solution we make use of a 4 layer MLP with structure as shown in the figure, and train the model for 10 epochs with **categorical_crossentropy** loss function,  **rmsprop** optimizer and **accuracy** as metric.

<p align="center">
  <img src="https://github.com/Pratham1807/Mnist-1/blob/master/images/img-3.PNG">
</p>

After training, the model is capable of classifying handwritten digits with an accuracy of 96.73%

<p align="center">
  <img src="https://github.com/Pratham1807/Mnist-1/blob/master/images/img-4.PNG">
</p>
