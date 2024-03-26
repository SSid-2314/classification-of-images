# Image Classification of Dogs and Cats
This repository contains code for image classification of dogs and cats using convolutional neural networks (CNNs).
The images are imported directly from the web for both training and testing purposes.
The model is trained using the Rectified Linear Unit (ReLU) activation function for training and validation, while the Sigmoid activation function is utilized for testing.
Clone the repository to your local machine:  git clone https://github.com/your-username/dogs-cats-image-classification.git
Install the required dependencies:  pip install -r requirements.txt
Run the main script to train and test the model:   python main.py

# Dataset
The dataset used for this project consists of images of dogs and cats. 
These images are fetched directly from the web during the training and testing phases.

# Training
During the training phase, the CNN model is trained using the ReLU activation function. 
The training data is fed into the model, and the weights are updated iteratively to minimize the loss function.

# Validation
Validation is performed during the training phase to ensure that the model is not overfitting to the training data. 
The validation set is used to evaluate the model's performance on unseen data.

# Testing
After training, the model is tested using the Sigmoid activation function.
The testing data, also fetched directly from the web, is passed through the trained model to predict whether the images contain a dog or a cat.
