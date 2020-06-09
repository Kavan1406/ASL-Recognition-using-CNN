## Objective

The objective of this project is to build a model to identify American Sign Language characters.


## Dataset

Dataset contains 87000 images, 3000 images for each of 29 classes. The dimensions of images are 256x256 pixels.
The Dataset used can be found [here](https://www.kaggle.com/grassknoted/asl-alphabet). 

The classes are as follows:
- English Alphabets (A-Z)
- Space
- Delete
- Nothing


## Methodology

First, we reduce the dimension of the images to 64x64 pixels. Then, convert the data into pixels and store it in a numpy array and finally, split it into train and test sets with 80/20 ratio.

Secondly, we build a Convolutional Neural Network to classify our images. 
We supply the training set for training with 10 epochs and separate 10% of training data for validation purpose.

Lastly, we test our model with testing set to check the accuracy of the model.


## Result

- Training Accuracy: 97.25%
- Validation Accuracy: 95.70%
- Testing Accuracy: 95.65%
