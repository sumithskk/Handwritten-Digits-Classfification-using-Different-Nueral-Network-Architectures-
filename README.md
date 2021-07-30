# Handwritten-Digits-Classfification-using-Different-Nueral-Network-Architectures-
 This project is a continuation of my earlier project 'Neural Network from Scratch' using Pandas and Numpy
 
 Github Link - https://github.com/sumithskk/Neural-Network

## MNIST Handwritten Digits Datasets
The MNIST Handwritten Digits dataset is considered as the “Hello World” of Computer Vision. 
The database is widely used for training and testing in the field of machine learning.
It was created by "re-mixing" the samples from NIST's original datasets.
The MNIST database contains 60,00 training images and 10,000 testing images and pixel size of 28x28.
![Digits](https://user-images.githubusercontent.com/42634704/127670780-8cf28ce3-8b6b-4e6d-a2f0-59ca8588c458.png)


##  Technical Aspects
Given that the problem is a multi-class classification task,input shape is 28x28 and, we know that we will require an output layer with 10 nodes in order to predict the probability distribution of an image belonging to each of the 10 classes. 

At each layers we have used either 'sigmoid' or 'Relu' activation functions and the loss function as 'Sparse Categorical Entropy' with optimizers 'Stochastic Gradient Descent' or 'Adam'. 
We used 'Keras Tuner Hyperband' for hyperparameter tuning of the model for the following parameters: Number of hidden layers, Number of Neurons in each of the Layers, Learning rate and Number of Epochs.

## Credits
  * The crash course on the MachineHack helped to get start with Tensorflow: https://machinehack.com/bootcamp/tensorflow-2-0-crash-course-79705640
  * Keras Documentation for Hyperparameter Tuning : https://colab.research.google.com/github/tensorflow/docs/blob/master/site/en/tutorials/keras/keras_tuner.ipynb
  * Thanks to Krish Naik, he helped a lot to learn from his youtube channel: https://www.youtube.com/user/krishnaik06
