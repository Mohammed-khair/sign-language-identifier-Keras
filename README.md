# Sign Language Symbol Identifier using CNN and TensorFlow Keras Functional API

This project was completed as an exercise in the Coursera course: Convolutional Neural Network.

## Overview

In this project, we aim to build a sign language symbol classifier capable of recognizing up to 6 different hand signs. To achieve this, we will leverage TensorFlow's Keras Functional API to construct the model architecture, which will be based on Convolutional Neural Networks (CNN).

## Dataset

The dataset used for training and testing the model contains images of various hand signs representing different symbols in sign language. The dataset has been preprocessed and split into train and test sets.

## Instructions

1. To view the project notebook, click on the following link: [Sign Language Identifier Notebook](https://colab.research.google.com/github/Mohammed-khair/sign-language-identifier-Keras/blob/main/Mini_sign_language_identifier_Keras.ipynb)

2. The notebook contains all the code necessary to train and evaluate the sign language symbol identifier. It covers the following steps:

   - Loading and splitting the dataset into training and testing sets.
   - Normalizing the input image vectors and reshaping the output vectors.
   - Implementing the CNN model with the following architecture:
     ```
     CONV2D -> RELU -> MAXPOOL -> CONV2D -> RELU -> MAXPOOL -> FLATTEN -> DENSE
     ```
   - Compiling the model using the Adam optimizer and categorical crossentropy loss.
   - Training the model for 100 epochs.

3. The model's performance metrics, including loss and accuracy, will be displayed during training.

## How to Use the Code

To use the code and train the sign language symbol identifier on your own dataset or make improvements to the model, follow these steps:

1. Install the required libraries and dependencies. Ensure you have TensorFlow, Keras, and other necessary packages installed.

2. Download the dataset or prepare your custom dataset in a format suitable for image classification tasks.

3. Use the provided notebook or integrate the relevant sections of the code into your own project.

4. Make any necessary modifications to the model architecture or hyperparameters to suit your specific use case.

5. Train the model and monitor its performance.

## Model Evaluation

After training the model for 100 epochs, the training loss, training accuracy, validation loss, and validation accuracy will be available for evaluation. You can analyze these metrics to assess the model's performance on the sign language symbol identification task.

## Conclusion

Building a sign language symbol identifier using Convolutional Neural Networks and TensorFlow Keras Functional API is an exciting project that showcases the potential of deep learning in real-world applications. By following the provided notebook and instructions, you can easily replicate the experiment or adapt it for your own image classification projects.

For any questions or feedback, please feel free to contact the project author. Happy coding!
