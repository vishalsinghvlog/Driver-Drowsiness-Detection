# Driver-Drowsiness-Detection

This is a project implementing Computer Vision and Deep Learning concepts to detect drowsiness of a driver.

# Description

In this deep learning model which first detect the face and eyes and based on the status of the eyes if the eyes are closed more than usual time then it can generate an alarm. This can be used by riders who tend to drive for a longer period of time that may lead to accidents.

# Technologies used

Python, OpenCV, Tensorflow, Keras

# Code Requirements

Python 3
Open cv

# Model

Reading all the images from the dataset and converting them into an array for Data & Labels.
Random shuffle is used to minimize overfitting
Using TensorFlow, import a Keras image classification model, optionally loaded with weights pre-trained on ImageNet. model = tf.keras.applications.mobilenet.MobileNet()
Use Tranfer Learning to create new model from above pretrained model
A single unit dense layer is acting as output for binary classification with activation set to Sigmoid
Optimizer is set to Adam.
For realtime time eyetracking in videos, use Haar Cascades frontal face algorithm.
