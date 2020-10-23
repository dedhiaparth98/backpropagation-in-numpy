# backpropagation-in-numpy
Classification on MNIST dataset using Dense Neural Network with backpropagation in Numpy

The NeuralNetwork class defined in the notebook takes two parameters one is the list of Dense units and other is the batch size. In the list of Dense Units, the last layer would be softmax and has to be 10 for MNIST and the first number is the flattened input, for MNIST it's 784. In between, any number could be put and the network will apply back propagation along all the layers. A train function is provided in the class which takes the number of epochs, Traning and Validation data as input. Print statements have been added to monitor the loss. 

I have not added callbacks like early stopping, learning rate reducer, etc. This repository was made after learning the mathematics of the back-propagation algorithm for Dense Layers and solely for understanding the maths.
