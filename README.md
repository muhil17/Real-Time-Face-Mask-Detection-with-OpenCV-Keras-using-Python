# Real-Time-Face-Mask-Detection-with-OpenCV-Keras-using-Python

During pandemic COVID-19, WHO has made wearing masks compulsory to protect against this deadly virus. In this tutorial we will develop a machine learning project – Real-time Face Mask Detector with Python.

In this repository, you will learn how to train a COVID-19 face mask detector with OpenCV, Keras (Deep Learning).

![image](https://user-images.githubusercontent.com/68604487/185742923-ae466a9b-4133-473d-acb3-359b41263fd6.png)

In order to train a custom face mask detector, we need to break our project into two distinct phases, each with its own respective sub-steps:

Training: Here we’ll focus on loading our face mask detection dataset from disk, training a model (using Keras) on this dataset, and then serializing the face mask detector to disk

Deployment: Once the face mask detector is trained, we can then move on to loading the mask detector, performing face detection, and then classifying each face as with_mask or without_mask

Let’s take a look at the dataset we’ll be using to train our COVID-19 face mask detector.

![image](https://user-images.githubusercontent.com/68604487/185742995-b19a3aef-41fa-4c55-8200-b6a21f0ee882.png)

This dataset consists of 1,509 images belonging to two classes:

with_mask: 755 images
without_mask: 754 images

Our goal is to train a custom deep learning model to detect whether a person is or is not wearing a mask.

