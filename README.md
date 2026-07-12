# Image_Classification_Project
Simple image classification project using Google Teachable Machine and Python.
Image Recognition using Teachable Machine


Project Overview

This project uses Google Teachable Machine to build an image recognition model that classifies images into two categories: Crocodile and Turtle. After training, the model was exported and used in Google Colab with Python to predict the class of a new image.

Steps

Opened Google Teachable Machine and selected the Image Project.

Created two classes: Crocodile and Turtle.

Uploaded multiple images for each class.

Trained the model using the uploaded images.

Evaluated the model to check its prediction accuracy.

Exported the trained model in TensorFlow/Keras format.

Opened Google Colab and uploaded the exported model files.

Wrote a Python script to:

Load the trained model.

Load a test image.

Preprocess the image.

Predict whether the image is a Crocodile or a Turtle.

Display the predicted class with its confidence score.

Files Included

keras_model.h5 – Trained model.


labels.txt – Class labels.


predict.py (or Colab notebook) – Python code for prediction.


test_image.jpg – Sample image used for testing.

screenshot.png – Screenshot of the prediction result.


Tools Used

Google Teachable Machine

Google Colab

Python

TensorFlow

NumPy

Pillow
