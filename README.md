**Title**:Hat or No Hat Detection Image Classifier

**Project Description**:

This repository contains code for a deep learning model to classify images as containing a person wearing a hat or not. The model is built using TensorFlow and Keras, leveraging transfer learning with a pre-trained InceptionV3 model.

**Overview**
The task of hat detection has various applications. This project aims to develop a robust image classifier capable of accurately identifying the presence of hats in images.

**Dataset**
test_set/ - the test set directory containing exactly 1490 image files.

**Features**
Utilizes transfer learning with a pre-trained InceptionV3 model for feature extraction.
Adds additional layers on top of the pre-trained model for binary classification.
Provides functionality to load images, preprocess them, and make predictions.
Outputs predictions in a CSV file for easy evaluation and analysis.

**Requirements**
Python 3.x
TensorFlow 2.x
NumPy
Pandas

**Usage**
Download the pre-trained InceptionV3 model weights from the TensorFlow Hub and place them in the models directory.
Prepare your dataset:
Organize your images into two folders: hat and no_hat, containing images with and without hats, respectively.
Ensure that the images are in JPEG format and resized to 224x224 pixels.
Set the test_set_folder to the path where the folder containing images is there.
Run the hat_detection.py script to make predictions:
The predictions will be saved in a CSV file named predictions.csv.

**Model Evaluation**
The performance of the model can be evaluated using classification metrics such as Categorization accuracy.

**Acknowledgements**
This project is a competition hosted in Kaggle environment and is graded by Categorized Accuracy.


