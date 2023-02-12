# Inception-V3
In this project i have used a Inception V3 model to test if a tomato leaf is infected or not.
you can get the Dataset from "https://www.kaggle.com/datasets/kaustubhb999/tomatoleaf"


# Tomato Leaf Disease Classifier
A deep learning model to classify tomato leaf diseases using TensorFlow and Keras. The model is based on the InceptionV3 architecture and is trained on images of tomato leaves. The goal of the model is to accurately identify and diagnose the type of leaf disease present in the images.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
You will need to have the following packages installed:

TensorFlow

Keras

Numpy

Matplotlib

Glob

Pillow

## Installing
You can install the packages using pip:
![image](https://user-images.githubusercontent.com/102272183/218294229-a3825d8b-0ae7-47d0-8047-95cb25dc048a.png)

## Running the code
The code reads in images of tomato leaves and trains a deep learning model to classify the images into one of 10 different classes, each representing a different type of leaf disease. The model uses the InceptionV3 architecture as a base and adds a few additional layers to make predictions.

The code also includes image augmentation, which helps to increase the size of the training dataset and reduce overfitting. The model is trained using the Adam optimizer and the categorical crossentropy loss function.

After training, the model is evaluated on a validation set and its performance is reported in terms of accuracy and loss.

## Conclusion
This model demonstrates the potential of deep learning for diagnosing plant diseases. By accurately identifying the type of disease present in images of tomato leaves, it can help farmers and plant experts make more informed decisions about treatment and management strategies. The model can be further improved and adapted for other types of plants and diseases by using a larger and more diverse training dataset.
