<h1 align="center">
MNIST Classification
</h2>
<p align="center">

## Overview
This repository contains code written explicitly in [Python 3](https://www.python.org/) and especially in [Pytorch](https://pytorch.org/) for MNIST Classification.

## MNIST
MNIST is a database of handwritten digits that has a training set of 60,000 examples and a test set of 10,000 examples. It is a subset of a larger set available from NIST. The digits have been size-normalized and centered in a fixed-size image. It is a good database for people who want to try learning techniques and pattern recognition methods on real-world data while spending minimal efforts on preprocessing and formatting. More details can be found [here](http://yann.lecun.com/exdb/mnist/).

## Requirements
- Python3
- Pytorch
- Torchvision
- Numpy
- Matplotlib

## Install the necessary libraries
The first step in order to run this code is to download the necessary libraries. Python has a tremendous amount of libraries and this is one of its strongest advantages. Python comes with a package installer and manager called [PIP](https://pypi.org/project/pip/), which is by default installed from version 3.4 onwards. In order to install the libraries, run the following command on your terminal:
```
$ pip install -r requirements.txt
```
The dollar sign ```$``` means that the following command should be written in terminal. Don't write this sign in terminal. It is just a symbol to make our lifes easier.

If you have problems installing Pytorch, have a look [here](https://pytorch.org/).

## Begin!
All the information needed about downloading MNIST dataset, creating, training and evaluating the dataset are in the [Jupyter Notebook](MNIST_Classification_using_Neural_Networks_with_Pytorch.ipynb).