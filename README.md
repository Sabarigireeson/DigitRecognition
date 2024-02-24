# MNIST Digit Recognition with OpenCV

This project uses TensorFlow to train a model on the MNIST dataset and then uses OpenCV to predict digits from a webcam feed.

## Dependencies

- TensorFlow
- Numpy
- OpenCV
- Matplotlib
- PIL

## How to Run

1. Ensure that you have all the required dependencies installed.
2. Run the script using Python 3.

## Code Overview
The code can be divided into three main parts:

1.Data Loading and Preprocessing: The get_mnist_data function is used to load the MNIST dataset and normalize the images.

2.Model Training: The train_model function is used to define and train a simple neural network using TensorFlow. The model is trained to achieve at least 99% accuracy.

3.Digit Prediction with OpenCV: The start_cv function captures video from the webcam, processes the frames, and uses the trained model to predict digits.
