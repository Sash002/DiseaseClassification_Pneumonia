# DiseaseClassification_Pneumonia

## Medical X-ray Image Classification using Convolutional Neural Networks

This repository contains code for training a convolutional neural network (CNN) to classify medical X-ray images as either normal or pneumonia.

## Getting Started
To get started, you will need to install the following dependencies:

Python 3
Keras
TensorFlow
NumPy
Matplotlib
Once you have installed the dependencies, you can clone the repository and run the following command to train the CNN:

python train.py

This will train the CNN on the dataset of X-ray images included in the repository. The trained model will be saved in the models directory.

## Evaluating the Model
To evaluate the model, you can run the following command:

python evaluate.py

This will print the accuracy, precision, and recall of the model on the test set.

## Using the Model
The trained model can be used to classify new X-ray images. To do this, you can run the following command:

python predict.py <path_to_image>

This will print the predicted class for the image.

## The application was built and deployed using streamlit. 
Link to the webapp: https://diseaseclassificationmadebysaswati.streamlit.app/
