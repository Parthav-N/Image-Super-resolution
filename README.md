# Image super-resolution using autoencoders

This project contains Python code to perform image super-resolution using autoencoders. The goal is to train an autoencoder to take low-resolution images as input and generate high-resolution images as output.

## Table of Contents
* Dataset
* Installation
* Usage
* Model Architecture
* Results
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

pip install tensorflow opencv-python tqdm matplotlib
