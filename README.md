# Image super-resolution using autoencoders

This project contains Python code to perform image super-resolution using autoencoders. The goal is to train an autoencoder to take low-resolution images as input and generate high-resolution images as output.

## Table of Contents
* Dataset
* Installation
* Code
* Model Architecture
* References

## Dataset
The dataset consists of low-resolution images of size 256x256. The dataset is divided into three sets - training set, validation set, and test set. The training set contains 700 images, the validation set contains 130 images, and the test set contains 25 images. The images are stored in the following directories: 

Raw Data: 
* High-res
* Low-res


## Installation

* Python 3.6 or above

* TensorFlow 2.x

* Keras

* OpenCV

* tqdm

* Matplotlib

You can install the required packages using pip: 

`pip install tensorflow opencv-python tqdm matplotlib`

## Code

The code for this project is present in the super_resolution_2.ipynb file. The notebook includes the following sections:

* Data preparation: reading in and preprocessing the data (high and low resolution images)
* Model building: defining the architecture of the autoencoder model
* Model training: training the model on the prepared data
* Model evaluation: evaluating the performance of the trained model on a test set
* Results visualization: visualizing the output of the model on sample test images

## Model Architecture

The model architecture is an autoencoder with skip connections. The autoencoder consists of a series of downsampling and upsampling layers. The downsampling layers reduce the resolution of the image, while the upsampling layers increase the resolution of the image. The skip connections help preserve the details of the image during the downsampling and upsampling process.

The model architecture is as follows:

![image](https://user-images.githubusercontent.com/92369070/230563035-915bc3d6-4ce5-4661-bb89-0dd9c0ce93c9.png)

## References
* [Autoencoders](https://github.com/mainak-ghosh/AutoEncoder)
* Tensorflow
* Keras




