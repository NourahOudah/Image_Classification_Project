# Image_Classification_Project
Simple image classification project using Google Teachable Machine and Python.
Image Recognition using Teachable Machine


Project Overview

This project uses Google Teachable Machine to build an image recognition model that classifies images into two categories: Crocodile and Turtle. After training, the model was exported and used in Google Colab with Python to predict the class of a new image.

Steps

1-Opened Google Teachable Machine and selected the Image Project.

2-Created two classes: Crocodile and Turtle.

3-Uploaded multiple images for each class.

4-Trained the model using the uploaded images.

5-Evaluated the model to check its prediction accuracy.

6-Exported the trained model in TensorFlow/Keras format.

7-Opened Google Colab and uploaded the exported model files.

8-Wrote a Python script to:

1-Load the trained model.

2-Load a test image.

3-Preprocess the image.

4-Predict whether the image is a Crocodile or a Turtle.

5-Display the predicted class with its confidence score.

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
