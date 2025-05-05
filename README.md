# Digit-Classification

# Digit Multiclass Classification

This project demonstrates a multiclass classification model using the MNIST dataset to recognize handwritten digits (0-9). The model is built using TensorFlow and Keras, achieving high accuracy in classifying digits.

## Project Overview

- **Objective**: Train a neural network to classify handwritten digits from the MNIST dataset.
- **Dataset**: MNIST dataset containing 60,000 training images and 10,000 test images of handwritten digits (28x28 pixels).
- **Model**: A sequential neural network with:
  - Flatten layer to convert 2D images into 1D arrays.
  - Dense layers with ReLU activation and Batch Normalization.
  - Softmax output layer for multiclass classification.

## Key Features

- **Data Preprocessing**: Normalizes pixel values to the range [0, 1].
- **Model Architecture**: Includes Batch Normalization for stable training.
- **Training**: Uses the Adam optimizer and sparse categorical cross-entropy loss.
- **Evaluation**: Achieves ~97.36% accuracy on the test set.

## Results

- **Training Accuracy**: ~99.37%
- **Validation Accuracy**: ~97.57%
- **Test Accuracy**: ~97.36%

## Files

- `Digit_Multiclass_Classification.ipynb`: Jupyter Notebook containing the complete code.
- `README.md`: This file.

## Future Improvements

- Experiment with deeper architectures or convolutional layers (CNNs) for better performance.
- Add data augmentation to improve generalization.
- Deploy the model as a web or mobile application for real-time digit recognition.
