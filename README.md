###     **computer-vision**
#     Image Segmentation based on the U-Net architecture

### Overview

In this notebook, we’ll build a [Convolutional Neural Network](https://www.ibm.com/topics/convolutional-neural-networks)  based on the [U-Net architecture](https://www.geeksforgeeks.org/u-net-architecture-explained/) to perform image segmentation on the [Oxford Pets dataset](http://www.robots.ox.ac.uk/~vgg/data/pets/data/images.tar.gz). Image segmentation allows us to identify and label each pixel in an image, which is useful for tasks that require detailed recognition, such as separating pets from the background in photos.

### Model

![img/u-net-architecture.png](https://miro.medium.com/v2/resize:fit:828/format:webp/1*x0kR2rGlTibVbu8InCNBVg.jpeg)

This deep neural network is implemented with Keras functional API, which makes it extremely easy to experiment with different interesting architectures.

## How to use

### Dependencies

This tutorial depends on the following libraries:

* Tensorflow
* Keras >= 1.0

Also, this code should be compatible with Python versions 3.10-3.12.


### Following steps:

    1.  Load and explore the dataset
    2.  Preprocess the images and masks
    3.  Define and build the U-Net model
    4.  Train the model using a learning rate scheduler and early stopping
    5.  Visualize the model's performance with sample predictions
