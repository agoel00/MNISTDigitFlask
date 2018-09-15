MNIST Digit Recognition Web App

## Demo
!()[mnist_demo.gif]

## Introduction

Flask web application which predicts handwritten digits (0-9) drawn by the user. 

It uses Random Forest Classifier algorithm to classify the handwritten digits.

The model has been trained and pickled on my local machine achieving a maximum accuracy of 96.7% with 300 trees. This
project uses Python 3.7

## Requirements
1. Flask
2. Scikit-learn
3. Numpy
4. Scikit-image
5. Scipy
6. Matplotlib

## Usage
To run this project on your computer, first clone this repository
>git clone 
>cd MNISTDigitFlask

Install all the requirements using
>pip install requirements.txt

Train and save the model using the Jupiter notebook and then
>cd digit_classifier

And run the flask app
>python srv.py

