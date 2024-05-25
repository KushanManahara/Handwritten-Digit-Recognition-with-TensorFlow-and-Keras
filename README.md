# Handwritten Digit Recognition with TensorFlow and Keras

This repository contains code for a handwritten digit recognition project using TensorFlow and Keras. The project aims to build, train, and evaluate a neural network model capable of recognizing handwritten digits from the MNIST dataset.

## Project Overview

The main components of the project include:

1. **Data Preprocessing**: The MNIST dataset is loaded and preprocessed to normalize pixel values.

2. **Model Building**: A neural network model is constructed using Keras, consisting of input layer, hidden layers with ReLU activation, and output layer with softmax activation.

3. **Model Training**: The model is trained on the training data using the Adam optimizer and sparse categorical crossentropy loss function.

4. **Model Evaluation**: The trained model is evaluated on the test data to assess its performance in terms of accuracy.

5. **Visualization**: TensorBoard callback is used to visualize model training metrics such as loss and accuracy.

6. **Prediction**: The trained model is used to make predictions on new handwritten digit images.

7. **Confusion Matrix**: A confusion matrix is computed to analyze the model's performance in more detail.

## Repository Structure

- `mnist_handwritten_digit_recognition.ipynb`: Jupyter notebook containing the code for the project.
- `README.md`: This file providing an overview of the project and instructions for running the code.
- `logs/`: Directory containing logs for TensorBoard visualization.
- `requirements.txt`: File listing the required Python libraries and their versions.

## Getting Started

To run the code, follow these steps:

1. Clone this repository to your local machine.
2. Install the required Python libraries listed in `requirements.txt`.
3. Open and run the `mnist_handwritten_digit_recognition.ipynb` notebook using Jupyter.

## Dependencies

- TensorFlow
- Keras
- NumPy
- Matplotlib

## Credits

This project is developed by [Your Name] as a part of [Project/Study/Assignment Name].

