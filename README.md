# Improving CNN Animal Image Classification
This repository focuses on comparing the following methods for addressing unbalanced classes and inconsistent image sizes when working with CNN's in tensorflow:

1. Apply class weights during fitting to put more weight on under represented classes
2. Progressive resizing using transfer learning and applying class weights to address the unbalanced data
3. Image augmentation through creating transformed copies of the original training images for the under represented classes

The goal of this project was to gain experience developing convolutional neural networks (CNN's) by developing three different models for classifying images of animals. The animals being compared for this project are cats, dogs, horses and zebras and the links to the datasets from Kaggle are listed below:

* cat and dog (https://www.kaggle.com/tongpython/cat-and-dog)
* horse2zebra (https://www.kaggle.com/arnaud58/horse2zebra)

The primary learning objectives from this project were the following:
* Learn how to work with unbalanced classes
* Learn how to work with inconsistent image sizes
* Learn how to work with small training sets

However through development of this project I learned new methods of working with the following packages and datatypes:
* Tensorflow and Keras
* openCV
* Images (using openCV and numpy)

More detailed discussion of the steps taken, and comparisons of the three methods mentioned above are included in the cnn_project.ipynb.

Other methods of improving a CNN's performance when faced with unbalanced data that are outside of the scope of this project at this time include the following:
* Variational Autoencoder (VAE)
* Generative Adversarial Network (GAN)
