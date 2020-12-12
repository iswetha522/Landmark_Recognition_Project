# Landmark Recognition Project
![LR Image](https://github.com/iswetha522/Landmark_Recognition_Project/blob/main/landmark_image.png)


## Description

This project mainly focus on finding the landmark of an image. Used two ways to predict the model.
- Without Transfer Learning
- With Transfer Learning
Compared which model gives more accuracy and then used that for predicting the test dataset. 

## Overview

Downloaded the data from Google Landmark Recognition from kaggle. After getting the data, cleaned it if there are any unwanted data for the analysis. After that started working on building the model.
The project used two ways to build the model:
- Used ResNet50 the pre - trained model as the base layer so that the model can get some pre - trained weights 
- Used Neural Network with random weights.
Trained with both the models and compared the loss and accuracy score. Once the accuracy score is statisfied started predicting the test set from the most accuracy scored model.

## Presentation 

Landmark Recognition Project Presentation PDF [Landmark Recognition Project PDF](https://github.com/iswetha522/Landmark_Recognition_Project/blob/main/Landmark_Recognition_Project.pdf).
## Language

- Python 3.8.3

## Tools used

- Jupyter Notebook
- Google Colab
  
## Libraries used

- from tensorflow.python.keras.models import Sequential
- from tensorflow.python.keras.layers import Dense
- from keras.applications.resnet50 import ResNet50
- from tensorflow.keras import layers
- from urllib.request import urlopen
- from io import BytesIO
- from PIL import Image
- matplotlib
- tensorflow
- traceback
- seaborn
- pathlib
- pandas
- numpy
- keras
- os



## Resources

- https://www.kaggle.com/c/landmark-recognition-challenge/data
- https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
- https://medium.com/@sdoshi579/convolutional-neural-network-learn-and-apply-3dac9acfe2b6
  