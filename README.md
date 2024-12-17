# CNN-for-Image-Classification
The final project for Machine learning/Deep learning course. Using tensorflow to create a Convoluted Neural Network (CNN) for cat/dog recognition.

## Installations

This project was written in python on Jupyter Notebook. The relevant python packages for this project are as follows:

- tensorflow
- tensorflow.keras.preprocessing.image (ImageDataGenerator)
- Numpy
- tensorflow.keras.preprocessing (image)
- tensorflow.keras.layers (Input)
- tensorflow.keras.callbacks (EarlyStopping)
- time
- os

## Project Description

In this project, we are going to build up a convolutional neural network (CNN) to be trained on training dataset (including 4000 images of dog and 4000 images of cat), and then be tested on the test dataset including 1000 images of dog and 1000 images of cat (for the sake of evaluation). Finally, you are supposed to input your model with images in "single_prediction" folder in order to classify the image as a dog or cat (making prediction using your model). 

## File Description

The project contains a dataset folder and the main notebook file named "CNN for Image Classification.ipynb". The dataset folder contains 3 subfolders named **single_prediction**, **test_set** and **training_set**. The **single_prediction** folder contains 2 images, which have to be identified as either cat or dog. The **test_set** and **training_set** folders each have two subfolders named ***cats*** and ***dogs***. The subfolders in **test_set** contain 1000 images each, used for testing the trained model whereas the subfolders in the **training_set** contain 4000 images each, used for training the model.

The explanation of the project is posted on [Medium](https://medium.com/@soumitro1604114/building-a-convolutional-neural-network-for-cat-vs-dog-classification-40d44f45d4c3)
