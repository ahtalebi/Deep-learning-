## **Learning goals:** 

1.   To get introduced with Convolutional Neural Networks (CNNs).
2.   To start working with image data.
3.   To train and test a CNN model for a multiclass classification task with PyTorch.


Convolutional Neural Networks (CNNs): are similar to ordinary neural networks.
They are made up of neurons that have learnable weights and biases.
The main difference is that CNNS mainly work on image data and apply the so called convolutional filters:
A typical CNN archtecture looks like the following?

It has:

Different convolutional layers.
Optional activation fucntions followed by Pooling layers.
lastely one or more fully connected layers

How data looks like:
CIFAR-10 dataset is available directely in PyTorch.

The CIFAR-10 dataset consists of 60000 32x32 colour images in 10 classes, with 6000 images per class. There are 50,000 training images and 10,000 test images. The 10 classes are: ‘airplane’, ‘automobile’, ‘bird’, ‘cat’, ‘deer’, ‘dog’, ‘frog’, ‘horse’, ‘ship’, ‘truck’. The images in CIFAR-10 are of size 3x32x32, i.e. 3-channel color images of 32x32 pixels in size.
