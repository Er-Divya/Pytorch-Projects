# Pytorch-Projects
This repository contains pytorch projects.

Project 1: Image Classification using CNN:

Dataset: CIFAR-10 

Model: Convolutional Neural Network CNN
CNN is a popular choice for image classification because they are capable of learning spatial hierarchies of features automatically like:

1. Edge
2. Texture
3. Shape

How does CNN work?

1. The first hidden layer after the input layer in CNN is usually a convolution layer. 
2. This layer applies filters on the input data to detect specific patterns like edges, textures, or shapes. 
3. The filter in the context of CNN is a small weight matrix that often has a 3*3 or 5*5 size. 
4. Each filter is sensitive to a particular feature of the input data.
5. These filters are learned during the training process to properly identify a particular feature concerning the training data.
6. This filter or weight matrix is applied to the input data by covering a small portion of input data across width and height taking one step at a time.
7. The newly generated values also form a matrix called feature maps that highlights the presence and intensity of various features mentioned in step 2. 
8. These feature maps are passed through the non-linear activation functions in the next steps. 
9. These non-linear functions introduce non-linearity in the feature maps to understand more complex patterns.
10. ReLU and its variants are common activation functions used by CNN.
11. After the first hidden layer, the following hidden layers can have additional convolution, pooling, and fully connected layers.
12. Pooling layers are used immediately after the convolutional layers in the CNN.
13. These layers reduce the spatial dimensions (width and height) of the feature maps which results in the reduction of parameters and computation in the network making systems more efficient.
14. The fully connected or dense layers are present after the previous two layers in a CNN.
15. Each neuron in a fully connected layer is connected to every neuron in the previous layer to learn the global pattern in the input data.
16. This global representation of the input data is combined and used by the fully connected layer to perform required tasks like classification of the images into predefined classes.
17. The output layer or softmax layer is a fully connected layer that uses the softmax activation function to determine the probability of an input belonging to each of a predefined set of classes.
