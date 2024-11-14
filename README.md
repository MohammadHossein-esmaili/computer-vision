###     **computer-vision**
#     Image Segmentation based on the U-Net architecture
[![forthebadge](https://forthebadge.com/images/badges/made-with-python.svg)](https://www.python.org/)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/https://github.com/MohammadHossein-esmaili/computer-vision/blob/main/pet_image_segmentation_Unet.ipynb)


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

### run
you can just run this notebook
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/https://github.com/MohammadHossein-esmaili/computer-vision/blob/main/pet_image_segmentation_Unet.ipynb)

## Following steps

    1.  Load and explore the dataset
    2.  Preprocess the images and masks
    3.  Define and build the U-Net model
    4.  Train the model using a learning rate scheduler and early stopping
    5.  Visualize the model's performance with sample predictions


## About Keras

Keras is a minimalist, highly modular neural networks library, written in Python and capable of running on top of either TensorFlow or Theano. It was developed with a focus on enabling fast experimentation. Being able to go from idea to result with the least possible delay is key to doing good research.

Use Keras if you need a deep learning library that:

allows for easy and fast prototyping (through total modularity, minimalism, and extensibility).
supports both convolutional networks and recurrent networks, as well as combinations of the two.
supports arbitrary connectivity schemes (including multi-input and multi-output training).
runs seamlessly on CPU and GPU.
Read the documentation [Keras.io](http://keras.io/)


