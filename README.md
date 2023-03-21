## ANN using TensorFlow 2.0 for MNIST and Regression

This notebook contains two machine learning models built using TensorFlow 2.0: one for MNIST digit classification and one for regression.

#MNIST Digit Classification

The first section of the notebook uses a neural network to classify images of handwritten digits from the MNIST dataset. The neural network architecture includes two hidden layers with 128 and 64 neurons respectively, and a softmax output layer. The model is trained using stochastic gradient descent with a learning rate of 0.01 over 10 epochs. The final accuracy on the test set is reported.

To run this section of the notebook, simply follow the instructions in the code cells and run them in order. The notebook will automatically download the MNIST dataset and preprocess the data for training and testing.

#Regression

The second section of the notebook uses a neural network for regression on a synthetic dataset. The neural network architecture includes two hidden layers with 32 and 16 neurons respectively, and a linear output layer. The model is trained using mean squared error loss with a learning rate of 0.01 over 100 epochs. The final mean squared error on the test set is reported.

To run this section of the notebook, follow the instructions in the code cells and run them in order. The notebook will automatically generate the synthetic dataset and split it into training and testing sets.

Dependencies
This notebook requires TensorFlow 2.0 and the following Python libraries:

.numpy
.matplotlib
